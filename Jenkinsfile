pipeline {
  agent {
    dockerfile {
      dir 'docker'
    }
  }

  stages {
    stage('Install dependencies') {
      steps {
        sh '/usr/bin/nuget restore'
      }
    }
  }
}
