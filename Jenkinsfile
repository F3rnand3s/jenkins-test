node{
  agent { dockerfile true }
  stage('SCM Checkout'){
    git 'https://github.com/F3rnand3s/jenkins-test'
  }
  stages {
      stage('Test') {
          steps {
              sh 'node --version'
          }
      }
  }
}
