pipeline {
    agent any

    stages {
        stage('SCM') {
            steps {
                // Get some code from a GitHub repository
                echo 'hii scm run'
               //git branch: 'master', url: 'https://github.com/vimallinuxworld13/simple-java-maven-app.git' 
               		sh 'touch index.html'
                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
	    steps {
			sh 'cp index.html /var/www/html'
			echo 'copied the file to webserver'
	    }
	   }
        stage('hii'){
	    steps{
            echo 'hii from jenkins'
        }
           
        }
    }
}
