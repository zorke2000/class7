properties([pipelineTriggers([cron('* 1 * * *')])])

pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                echo 'running from git'
                bat "python hello.py"
            }
        }
    }
}
