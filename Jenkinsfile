pipeline {
    agent any
    
    tools
    {
       maven "Maven"
    }
     
    stages {
      stage('checkout') {
           steps {
             
                git branch: 'main', url: 'https://github.com/prit2477/demosample.git'
          }
        }
}

         stage('Execute Maven') {
           steps {
             
                sh 'mvn package'             
          }
        }
        
