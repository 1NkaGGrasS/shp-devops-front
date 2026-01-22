pipeline{
  agent{
    docker{
      image 'node:14'
      args '-v $WORKSPACE:/usr/src/app'
    }
  }
  stages{
    stage('install dependencies'){
      steps{
        script{
          sh 'npm install'
        }
      }
    }
  }
}
