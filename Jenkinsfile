pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(branch: 'main', url: 'https://github.com/prit2477/demosample.git', poll: true)
        waitForQualityGate true
      }
    }

  }
}