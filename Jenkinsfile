pipeline{
  agent any

  stages {
    stage("Starting"){
      steps{
        sh 'echo Starting'
      }
    }
    stage("Unit Tests"){
      steps {
        sh './helper test'
      }
    }
  }
}
