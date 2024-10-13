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
                '''
                apt update
                apt install jq -y
            }
        }
    }
}
