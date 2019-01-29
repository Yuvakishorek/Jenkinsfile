pipeline {
    agent any 
    stages {      
        stage('Build') { 
            steps {
           sh "mvnBuild"
            }
        }
        stage('Test') { 
            steps {
          sh "mvnTest"
            }
        }
        stage('Deploy') { 
            steps {
              sh "mv Deploy"
            }
        }
    }
}
