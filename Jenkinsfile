node{
  stage('SCM Checkout'){
    git 'https://github.com/F3rnand3s/jenkins-test'
  }
  agent { dockerfile true }
  stages {
      stage('Test') {
          steps {
              sh 'node --version'
          }
      }
  }
}
