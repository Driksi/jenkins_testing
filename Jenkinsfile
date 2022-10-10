pipeline {
    agent { 
	docker {
	args "-u root" 
	image 'python:3.10.7-alpine' 
	} 
	}
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}