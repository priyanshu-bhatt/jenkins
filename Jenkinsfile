pipeline {
    agent any

    stages {
        stage('SCM') {
            steps {
                // Get some code from a GitHub repository
                echo 'hii scm run'
               git branch: 'master', url: 'https://github.com/vimallinuxworld13/simple-java-maven-app.git' 
               		//sh 'touch index.html'

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
}

	   }
        stage('Build'){
	    steps{
            	 sh 'clean package'
	   
        }
           
        }
    }
}
