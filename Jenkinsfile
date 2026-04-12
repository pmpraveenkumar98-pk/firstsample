pipeline  {
  agent any

  stages{
    stage('BUILD'){
      steps{
        sh 'touch logs'
        echo "Welcome to build"
      }
    }
    stage('TEST'){
      steps{
        sh 'ls'
        echo "Welcome to test"
      }
    }
    stage('DEPLOY'){
      steps{
        sh 'pwd'
        echo "Welcome to deploy"
      }
    }
    }
}
