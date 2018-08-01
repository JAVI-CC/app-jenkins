pipeline {
  agent any
  stages {
    stage('Inicio') {
      parallel {
        stage('Inicio') {
          steps {
            echo 'Hola desde stage Inicio'
          }
        }
        stage('javi') {
          steps {
            echo 'hola'
          }
        }
      }
    }
    stage('Test2') {
      steps {
        echo 'Hola desde stage 2'
      }
    }
  }
}