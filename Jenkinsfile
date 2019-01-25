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
	        sh "sudo docker-compose build"
		sh "sudo docker-compose up -d"                      
	    }    
	}
       
    }
}


