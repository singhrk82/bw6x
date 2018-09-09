pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Build', quietPeriod: 8)
        echo 'Done'
      }
    }
  }
}