pipeline {
    agent any

    stages {
        stage('Sentrio') {
            steps {
                sh "ls"
                sh "pwd"
                sh "git log --format=%B cfcef5f31fa4d98c05c0b668646a44fe39afd1a0...a49e132d1d978c4d6d18d53062b73aac70d956b5"
                sendDeploymentFinishedEvent environment: 'dev', application: "sample", release: "1.0.0-SNAPSHOT"
            }
        }
    }
}

