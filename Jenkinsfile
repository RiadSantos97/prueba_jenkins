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
        '''
      }
    }
    stage('Test') {
      steps {
        sh'''
        echo 'Imprime algo'
        echo 'Esto fue tomado del branch3'
        '''
      }
    }
    stage('Deploy') {
      steps {
        echo 'Imprime otra cosa'
      }
    }
  }
}
