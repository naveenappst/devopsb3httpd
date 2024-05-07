pipeline{
  agent any
  stages {
    stage ('QRBuild') {
      steps {
        echo "Build pipeline"
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
