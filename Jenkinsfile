pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/tsivareddy/devopstest.git'
            }
        }
        
         stage('Test') {
            steps {
               echo "Test"
             
            }
        }
    }
}
