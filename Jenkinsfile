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
      maven 'NPM_HOME'
  }
}