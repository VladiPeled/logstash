pipeline {
  agent any
  stages {
    stage('email') {
      steps {
        emailext(subject: 'vladi test', body: 'This is my email \\n I am testing it', to: 'vladi.kaplun@gmail.com')
      }
    }
  }
}