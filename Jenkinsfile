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
    stage ('Deploy to Dev') {
      steps {
        echo "Devstage"
      }
    }
    stage ('Deploy to Test') {
      steps {
        echo "Teststage"
  }
}
    stage ('Deploy to Satge') {
      steps {
        echo "Satge pipeline"
  }
    }
    stage ('Deploy to Prod') {
      steps {
        echo "Prod pipeline"
      }
    }
  }
}
