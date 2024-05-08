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
        echo "Docker Stage"
      }
    }
    stage ('Deploy to Dev') {
      steps {
        echo "Dev pipeline"
      }
    }
    stage ('Deploy to Test') {
      steps {
        echo "Test pipeline"
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
