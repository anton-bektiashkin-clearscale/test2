pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'node --version'
				sh "java -version 2>&1 | head -n 1 | awk -F '"' '{print $2}'"
            }
        }
        
      
    }
}