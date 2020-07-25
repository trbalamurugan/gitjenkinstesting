pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Test'
      }
    }

    stage('') {
      steps {
        build(job: 'Test', quietPeriod: 1, wait: true)
      }
    }

  }
}