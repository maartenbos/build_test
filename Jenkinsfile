pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        echo 'Start Testing'
        sh 'bundle exec rspec'
      }
    }
  }
}