pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000 -p 5000:5000'
    }

  }
  stages {
    stage('BinariesDownload') {
      agent any
      steps {
        ansiColor(colorMapName: 'xterm') {
          sh '''echo #download Java
echo #download weblogic
wcho #download weblogic patches
'''
        }

      }
    }
  }
}