pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
        echo 'Do something'
        hostname
        echo 'Se imprimió el hostname tambien'
        '''
      }
    }
    stage('Test') {
      steps {
        echo 'Imprime algo'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Imprime otra cosa'
      }
    }
  }
}
