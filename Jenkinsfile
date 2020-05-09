pipeline {
  agent any
  stages {
    stage('Show readme') {
      agent any
      steps {
        checkout scm
        sh "cat README.md"
      }
    }
  }
}
