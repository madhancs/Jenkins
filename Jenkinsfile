pipeline {
    //agent { docker 'node:6.3' }
    agent {
      dockerfile true
    }
    environment {
      PATH='$PATH:/usr/local/bin'
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
