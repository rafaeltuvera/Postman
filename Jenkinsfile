pipeline {
    agent any
    stages {
	      stage('Run test') {
        	steps {
	          		bat "newman run UserAPIs.postman_collection.json"
	        }
        	
        }
    }
	tools {
      nodejs 'NPM_HOME'
  }
}