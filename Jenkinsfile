pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
        echo 'Do something'
        hostname
        echo 'Se imprimió el hostname tambien'
        pwd
        echo 'Todo bien'
        echo 'Prueba de webhook'
        echo 'Esto fue tomado del main'
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
