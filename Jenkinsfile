pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                echo 'hii scm run'
               git branch: 'master', url: 'https://github.com/vimallinuxworld13/simple-java-maven-app.git' 
               
                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
	   }
        stage('hii'){
	    steps{
            echo 'hii from jenkins'
        }
           
        }
    }
}
