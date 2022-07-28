pipeline {
  agent any
    
  stages {
        stage('see') { 
            steps {
                sh 'ls' 
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
