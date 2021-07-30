pipeline {
  agent any 

  stages {
    stage('build') {
      steps {
        sh 'pwd'
        touch testfile.txt
        stat testfile.txt
      }
    }

  }
}
