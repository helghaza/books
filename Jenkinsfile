pipeline {
  agent {
    node {
      label 'local'
    }

  }
  stages {
    stage('RetrieveSources') {
      steps {
        git 'https://github.com/helghaza/books.git'
      }
    }
    stage('BuildBinary') {
      steps {
        sleep 1
      }
    }
  }
}