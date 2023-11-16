pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''sh \'yarn\'
sh \'npx ng build\''''
      }
    }

  }
  environment {
    MAIL_ID = 'chenna.m@getster.tech'
    app_id = 'form'
  }
}