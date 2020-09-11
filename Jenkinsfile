pipeline {
    agent any
    stages {
        stage('Install dependencies') {
        	steps {
	          		bat "npm i newman -g"
	        }
        	
        }
	      stage('Run test') {
        	steps {
	          		bat "newman run UserAPIs.postman_collection.json"
	        }
        	
        }
    }
}