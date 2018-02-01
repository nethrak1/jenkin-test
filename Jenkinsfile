pipeline {
  agent any
  stages {
    stage('Backend') {
      steps {
        parallel(
          "Backend": {
            echo 'backend dev message '
            
          },
          "Backend2": {
            echo 'backend2 dev'
            
          },
          "Backeend": {
            echo 'backend3 dev'
            
          }
        )
      }
    }
    stage('Frontend') {
      steps {
        echo 'Frontend dev massage'
      }
    }
    stage('Final') {
      steps {
        echo 'Final dev'
      }
    }
  }
}
