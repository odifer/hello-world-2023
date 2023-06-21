pipeline {
    agent any
    tools {
        maven 'apache-maven-3.9.2'
        jdk 'jdk11'
     stages{
      stage('Hello'){
       steps {
         echo "Hello World"
       }
     }
      stage("build"){
        steps {
            sh "mvn clean package"
        }
      }
      }
}
