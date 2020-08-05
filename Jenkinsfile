def hello = "hello wordl"
pipeline {
    agent any

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
