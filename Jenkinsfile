pipeline {
  agent any
  stages {
    stage('1- gitclone') {
      steps {
        git(poll: true, url: 'https://github.com/Amarlanda/publis-spaient-demo.git')
      } // end of step 1
    }
    stage('2 - amartest') {
      steps {
        sh 'ls'
        sh 'cat Jenkinsfile'
        sh 'ls'
        sh 'ls'
        sh 'ls'

      }// end of step 2
    }
  }
}
