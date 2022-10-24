pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test') {
     steps {
        sleep 5
        echo 'Testing...'
     }
   }
   stage('Deploy') {
     steps {
        sleep 8
       echo 'Deploying...'
     }
   }
  }
}
