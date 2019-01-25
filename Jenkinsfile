pipeline {
    agent {
        label 'master'
    }
    options {
        skipDefaultCheckout()
    }
    stages {
	stage("startproject"){
	    steps {
	        sh "docker-compose build"
		sh "docker-compose up -d"                      
	    }    
	}
       
    }
}


