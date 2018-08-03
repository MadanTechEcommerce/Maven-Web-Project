#!groovy

node {
	   
	stage('Checkouting'){

          checkout scm
       }

       stage('BuildArtifact'){

          sh 'mvn install'
       }
	
       
}
