pipeline {
    agent any
    options {
               //Timeout counter starts BEFORE agent is allocated
               timeout(time: 1, unit: 'SECONDS')
             }
    stages {
         stage("build") {
             steps{
             echo "build the application"
              }
           }
          stage("test"){
            steps{
               echo "testing the application"
              }
            }
stage("deploy"){
    steps{
        echo "deploying the application"
       }
     }
   }
}
