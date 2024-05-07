pipeline{
  agent any
  stages {
    stage ('gitSCM') {
      steps {
        echo "Build Stage"
      }
    }
    stage ('Fortify Scan') {
      steps {
        echo "Executing Scans!!!"
      }
    }
    stage ('Dockerbuild') {
      steps {
        echo "Dockerbuild"
      }
    }
    stage ('devstage') {
      steps {
        echo "devstage"
      }
    }
  }
}
