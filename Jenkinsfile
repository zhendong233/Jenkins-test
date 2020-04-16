pipeline {
 agent any 
 stages {
  stage('Test') {
   steps {
       echo 'Hello World'
       bat 'docker run -t postman/newman_ubuntu1404 run https://www.getpostman.com/collections/0020c9c9f6297546a314'
   }
  }
 }
}
