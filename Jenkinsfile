pipeline{
  agent any
  
  stages{
    stage("Build"){
      steps{
        bat "\"C:\\Program Files\\apache-maven-4.0.0-beta-4\\bin\\mvn\" clean install"
      }
    }

    stage("Test"){
      steps{
        bat "\"C:\\Program Files\\apache-maven-4.0.0-beta-4\\bin\\mvn\" test"
      }
    }
  }
}
