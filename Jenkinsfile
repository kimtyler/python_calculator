pipeline {
	agent any
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python3 calculator.py
				"""
			} //steps
		} //stage("Run unit test")
				steps {
					sh """
						python3 -m pytest
					"""
				} //steps
	} //stages 
} //pipeline
