pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        dockerNode(image: 'node:lts-alpine')
      }
    }

  }
}