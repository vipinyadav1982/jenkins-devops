//Scripted Pipeline (Its Old Version of Jenkins File)

// Declarative
pipeline {
	//agent any
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('Build') {
			steps{
        echo "Build"
		}
		}
		stage('Test') {
			steps{
        		echo "Test"
	    			}
		}
		stage('Integration Test') {
			steps{
	    echo "Integration Test"
			}
		}
	}
		
		
}
