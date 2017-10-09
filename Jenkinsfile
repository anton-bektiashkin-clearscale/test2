pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh """
                node --version
                curl -L https://www.npmjs.com/install.sh | sh
                npm --version
                """
            }
        }
        
      
    }
}
