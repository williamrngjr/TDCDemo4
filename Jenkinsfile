pipeline {
  agent any
  stages {
    stage('allocate') {
      steps {
        node(label: 'Node1') {
          echo 'allocating Node 1'
        }
        
      }
    }
    stage('Stage2') {
      steps {
        echo 'Stage2'
      }
    }
  }
}