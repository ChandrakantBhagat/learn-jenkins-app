pipeline {
    agent {
        docker {
            image 'ubuntu:latest'
            args '-u root'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh '''
                apt update
                apt install jq -y
                '''
            }
        }
    }
}
