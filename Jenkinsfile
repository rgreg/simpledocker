
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                   echo 'Checking out the source code from github ...'
                   checkout scm

                   sh label: '', script: 'cp games_fn_v02.zip main.py audit_changes.py requirements.txt'

            }
        }
    }
}
