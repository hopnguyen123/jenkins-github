pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git branch: 'main', url: 'https://github.com/hopnguyen123/jenkins-github.git'
      }
    }
    // add more stages for build, test, deploy, etc.
  }
}
