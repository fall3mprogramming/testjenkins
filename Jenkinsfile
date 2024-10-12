pipeline{
  agent any
  
  stages{
    stage("Build"){
      steps{
        bat "\"C:\\Program Files\\apache-maven-3.9.9\\bin\\mvn\" clean install"
      }
    }

    stage("Test"){
      steps{
        bat "\"C:\\Program Files\\apache-maven-3.9.9\\bin\\mvn\" test"
      }
    }
  }
}
