pipeline {
    agent any

    stages {
        stage('Sentrio') {
            steps {
                sendDeploymentFinishedEvent environment: 'dev', application: "sample", release: "1.0.0-SNAPSHOT"
            }
        }
    }
}
