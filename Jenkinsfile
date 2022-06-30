pipeline {
    agent {
        label 'cpvm'
    }
    stages {
        stage('Build') { 
            agent {
                label 'cpvm'
            }
            steps {
                sh 'npm install' 
            }
        }
    }
}