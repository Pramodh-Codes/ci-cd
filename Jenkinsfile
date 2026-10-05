pipeline {
  agent any
     
  stages {
    stage('build'){
      steps{
        echo 'building...!'
  
      }
    }      
    stage('test'){
      steps{
        echo 'testing'
      }
    }
    stage('develop'){
      steps{
        echo 'developing'
      }
    }
    
    stage('Checkout'){
      steps{
        echo 'checking out...'
    } 
  }
}
  post{
    success{
      echo 'pipeline completed'
    }
    failure{
      echo 'pipeline failed'
    }
  }
}
