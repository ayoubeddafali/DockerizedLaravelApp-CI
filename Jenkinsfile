pipeline{
  agent any

  stages {
    stage("Starting"){
      steps{
        sh './helper up -d'
      }
    }
    stage("Unit Tests"){
      steps {
        sh './helper test'
      }
    }
  }
  post {
    sh './helper down'
  }
}
