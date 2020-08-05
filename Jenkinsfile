def hello = "hello wordl"
pipeline {
    agent any
parameters {
    choice choices: ['server1','server2','server3'],
    description:  'Servidor de origen',
    name: 'source_server'
    
    choice choices: ['server1', 'server2', 'server3'],
                description: 'Servidor de Destino',
                name: 'destino_server'
}
    stages {
        stage('Hello') {
            steps {
                script {
                    test(hello)
                }
            }
        }
    }
}
