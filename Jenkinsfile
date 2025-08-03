pipeline {
    agent any

    stages {
         stage('checkout'){
            steps{
                echo 'Checking out code'
            }
         }
      stage('Build') {
         steps {
           echo 'Building the project'
           sh 'echo "Simulating a build...Successs"'
         }
      }
      stage('Test') {
        steps{
          echo 'Running tests...'
          sh 'echo"Simulating tests...Success"'
        }
      }
      stage('Deploy') {
        steps{
          echo 'Deployment is not yet configured'
        }
      }
    }
}
      
