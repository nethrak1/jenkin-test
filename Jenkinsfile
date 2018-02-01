pipeline {
  agent any
  stages {
    stage('Backend') {
      steps {
        parallel(
          "Backend": {
            echo 'backend test message '
            
          },
          "Backend2": {
            echo 'backend2 test'
            
          },
          "Backeend": {
            echo 'backend3 test'
            
          }
        )
      }
    }
    stage('Frontend') {
      steps {
        echo 'Frontend massage test'
      }
    }
    stage('Final') {
      steps {
        echo 'Final test'
      }
    }
  }
}
