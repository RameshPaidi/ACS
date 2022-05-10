pipeline {
  agent none
  stages {
    stage ('Build') {
      agent { label 'bzzzmaven' }
      steps { ... }
    }
    stage ('Deploy') {
      agent { label 'bzzzproduction' }
      steps { ... }
    }
  }
}
