pipeline {
  agent { label 'node-1' }
  stages {
    stage('build') {
          steps {
        sh 'mvn clean install'
      }
    }
  }
}
