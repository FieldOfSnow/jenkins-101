pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script{
                    echo "Hello World"
                    echo "Path is: ${env.PATH}"
                    bat 'python --version'
                    bat 'python helloworld.py'
                }
            }
        }
    }
}
