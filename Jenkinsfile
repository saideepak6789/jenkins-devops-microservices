pipeline {
	//agent any
	//agent { docker {image 'maven:3.6.3'}}
	agent { docker {image 'node'}}
	stages{
		stage('Build') {
			steps {
				sh "node --version"
			}
		}
		stage('test') {
			steps {
				echo "test"
			}
		}
		stage('Intergartion test') {
			steps {
				echo "Intergartion test"
			}
		}				
	}
}