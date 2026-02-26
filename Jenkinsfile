pipeline {
  agent any 

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/clashofclans005/jenkinsdemo.git',
          branch: 'main'
      }
    }
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
