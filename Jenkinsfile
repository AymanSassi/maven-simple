pipeline{
agent any
stages{
  stage('Build'){
    steps{
    sh '/home/aiman/maven/bin/mvn clean install'
    }
  }
  stage('Test'){
    steps{
    sh '/home/aiman/maven/bin/mvn test'
    }
  }
}
}
    
