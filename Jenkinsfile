pipeline {
  agent {
    dockerfile {
      dir 'docker'
    }
  }

  stages {
    stage('Install dependencies') {
      steps {
        echo pwd()
        sh '/usr/bin/nuget restore'
      }
    }
  }
}
