pipeline {
    agent any

      tools{
            maven 'Maven-3.3.9'
            jdk 'Java-1.8.0_212'
      }

      stages {
        stage('Build') {
          steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
