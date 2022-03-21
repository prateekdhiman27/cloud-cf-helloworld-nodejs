pipeline {
  agent {
    docker { image 'ppiper/jenkins-master' }
    }
  stages {
    stage('prepare') {
      checkout scm
      setupCommonPipelineEnvironment script:this
      }
    stage('Build') {
      echo('tbd')
      }
    stage('deploy') {
      echo('tbd deploy')
    }
    }
}


/*node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('build') {
    mtaBuild script: this
}
}
*/
