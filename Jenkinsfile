pipeline {
   
  agent any
  stages {
    stage('git-pull'){
      steps{
        echo 'git clone'
      }
    }
    stage('Test'){
      steps {
        echo 'Test code'   
      }
    }
    stage('Build'){
      steps {
         echo 'Build code'  
      }
    }
    stage('Deploy'){
      steps {
          echo 'Deploy code'
      }
    }
  }
}
