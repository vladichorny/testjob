pipeline {
  agent { label 'master' }
  
  stages {
    stage('checkout') {
      steps {
        bat script: """
          echo "test"
        """
      }
    }
    stage('build') {
      steps {
        bat script: """
          echo "222"
        """
      }
    }
  }
}
