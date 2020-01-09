pipeline {
  agent any
  stages {
    stage('pre deployment email') {
      steps {
        mail(subject: 'vladi_test', body: 'This is a test email', to: 'vladi.peled@gmail.com', from: 'vladi.peled@gmail.com')
      }
    }
  }
}