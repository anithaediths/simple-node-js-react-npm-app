pipeline {
  agent any
    
  tools {nodejs "node"}
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
