pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Done'
        mail(subject: 'test email from jenkns', body: 'test email from jenkns', from: 'jenkins@zimmerbiomet.com', to: 'ranjeetkumar.singh@zimmerbiomet.com')
      }
    }
  }
}