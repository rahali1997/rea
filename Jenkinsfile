pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo 'step build'
               sh 'npm install'
            }
        }
     
          stage('test') {
            steps {
               echo 'step test'
            }
        }
        
          stage('deploy') {
            steps {
               echo 'step deploy'
            }
        }
               
    }
}
