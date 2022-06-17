pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Construir Docker'
        echo 'Montar imagen docker'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Prueba 1'
          }
        }

        stage('') {
          steps {
            echo 'Prueba 2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Despliegue'
      }
    }

  }
}