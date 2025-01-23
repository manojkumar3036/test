pipeline {
	agent any 
	stages {
		stage('Checkout'){
			steps {
				echo 'Checkout the application...'
			}
		}
		stage('Build'){
			steps {
				echo 'Build the application...'
			}
		}
		stage('Test'){
			steps {
				echo 'Build the application...'
			}
		}		
	}
	
	post {
		success {
			echo 'Build and deployment succeeded!'
		}
		failure {
			echo 'Build or deployment failed!'
		}
	}
		
}

