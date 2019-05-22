pipeline {
  agent none
  stages {
    stage('Build Image') {
      agent {
        docker { image 'python:3.6-alpine'}}
    }
  }
}
