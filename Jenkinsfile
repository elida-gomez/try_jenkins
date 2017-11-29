pipeline {
  agent any
  stages {
    stage('Inicio') {
      parallel {
        stage('Inicio') {
          steps {
            sh 'touch itworksallgood.txt'
            sleep 10
          }
        }
        stage('NextJiji') {
          steps {
            sh 'echo "Jenkins home $JENKINS_HOME"'
          }
        }
      }
    }
    stage('Phase2') {
      steps {
        echo 'Lalo Landa $WORKSPACE'
      }
    }
  }
}