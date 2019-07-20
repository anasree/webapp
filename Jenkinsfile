pipeline {
  agent any

  tools{
        maven 'Maven-3.5.3'
        jdk 'Java 8'
  }

    stages {
      stage('Build') {
        steps {
              sh 'mvn clean package'
      }
    }
  }
}
