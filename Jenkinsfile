pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/tsivareddy/devopstest.git'
                pwd
                ls -ltr
            }
        }
        
         stage('Test') {
            steps {
               echo "Test"
             
            }
        }
    }
}
