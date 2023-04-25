pipeline {
	//agent any
	//agent { docker {image 'maven:3.6.3'}}
	agent { docker {image 'node:3.6.3'}}
	stages{
		stage('Build') {
			steps {
				sh "mvn --version"
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