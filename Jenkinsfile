
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                   echo 'Checking out the source code from github ...'
                   checkout scm

                   sh label: '', script: 'docker build -t simple-web-app'
                
                   sh label: '', script: 'docker build -t simple-web-app'
          
            }
        }
    }
}
