pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                echo 'hii scm run'
               git branch: 'main', url: 'https://github.com/priyanshu-bhatt/jenkins-slave-maven.git' 
               
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
