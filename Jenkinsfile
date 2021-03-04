pipeline {
    agent any

    stages {
        stage('Sentrio') {
            steps {
                sh "ls"
                sh "git log"
                //sh "git log"
                sendDeploymentFinishedEvent environment: 'dev', application: "sample", release: "1.0.0-SNAPSHOT"
            }
        }
    }
}

