pipeline {
    agent { 
      dockerfile true
    }
    stages {
        stage('SCM Checkout'){
          steps {
            git 'https://github.com/F3rnand3s/jenkins-test'
          }
        }
        
        stage('Test') {
          steps {
            echo 'Hello World!'
          }
        }
    }
}
