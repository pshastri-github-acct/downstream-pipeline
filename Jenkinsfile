pipeline {
  agent any
  stages {
    stage('Received an event') {
      steps {
        echo 'I just received a testingCompleted event'
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('testingCompleted'))
  }
}