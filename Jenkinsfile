pipeline {
  agent any 
  tools {
    maven 'Maven'
  }
  stages {
    stage("build") {
      steps {
        sh "mvn install"
      }
    }
    stage ("test") {
      steps {
      }
    }
    stage ("deploy") {
      steps {
      }
    }
  }
}
