pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Front-end') {
            agent {
                docker { image 'node:lts-buster-slim' }
            }
            steps {
                sh 'node --version'
            }
        }

    }
}
