pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
           sh "mvn Build"
            }
        }
        stage('Test') { 
            steps {
          sh "mvn Test"
            }
        }
        stage('Deploy') { 
            steps {
              sh "mvn Deploy"
            }
        }
    }
}
