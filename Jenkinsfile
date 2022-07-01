pipeline {
    agent {
        label 'cpvm'
    }
    tools {nodejs "nodejs"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}