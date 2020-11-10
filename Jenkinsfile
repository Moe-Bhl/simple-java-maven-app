pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build maven app'
        sh '''cd scripts
sh run_build_deliver.sh'''
      }
    }

  }
}