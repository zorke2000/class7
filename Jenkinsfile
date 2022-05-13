pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'running from git'
                bat "python hello.py"
            }
        }
    }
}
