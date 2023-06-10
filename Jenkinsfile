pipeline {
	agent any
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/namika/Documents/devops-tools/apache-maven-3.8.8
'/mvn install'	                 }}
		stage('Deployment'){
		    steps {
			
			sh 'cp target/dakshu.war /home/namika/Documents/devops-tools/apache-tomcat-9.0.73/webapps '
	}
}}}
