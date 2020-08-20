pipeline {
  agent { label 'node-1' }
  stages {
    stage('Compile') {
          steps {
        sh 'mvn clean install'
      }
    }
  }
}
