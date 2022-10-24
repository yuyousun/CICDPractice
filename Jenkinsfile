pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
           sleep 5
          echo 'Building.66666666666666..'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test') {
     steps {
        echo 'Testing.11113333..'
        sleep 6
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying..1111.'
        sleep 9
     }
   }
  }
}
