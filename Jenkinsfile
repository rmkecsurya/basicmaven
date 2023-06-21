pipeline {
agent any
tools {
maven 'maven'
}
stages{
  stage("MavenVesion"){
    steps{
      sh 'mvn --version'
    }
  }
  stage("Maven clean"){
    steps{
      sh 'mvn clean'
    }
  }
  stage("Maven validate"){
    steps{
      sh 'mvn validate'
    }
  }
  stage("Maven compile "){
    steps{
      sh 'mvn compile'
    }
  }
  stage("Maven test"){
    steps{
      sh 'mvn test'
    }
  }
  stage("Maven package"){
    steps{
      sh 'mvn package'
    }
  }
}
}
