pipeline {
  agent any
  stages {
    stage('1- gitclone') {
      steps {
        git(poll: true, url: 'https://github.com/Amarlanda/publis-spaient-demo.git')
        sh 'ls'
      }
    } stage('2 - amartest') {
      steps {
        sh 'ls'
      }

    }
  }
}
