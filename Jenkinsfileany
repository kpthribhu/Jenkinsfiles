pipeline {
	agent any 
	stages {
		stage('Build') {
			steps {
				sh 'sleep 5; echo "This is a Build stage"'
			}
		}
		stage('Test'){
			steps {
				sh '''
					sleep 5
					echo "This is a Test stage"
				'''	
			}
		}
		stage('Deploy'){
			steps {
				sh '''
					sleep 5
					echo "This is a Deploy stage"
				'''
			}
		}
		stage('My-stage'){
			steps {
				sh '''
					sleep 5
					echo "This is a My-stage stage"
				'''
			}
		}	
	}
}
