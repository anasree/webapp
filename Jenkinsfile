pipeline {
    agent any

      stages {
        stage('Build') {
          steps {
            scripts{
                    def mvnHome = tool 'Maven 3.3.9'
                     sh "'${mvnHome}/bin/mvn' -Dintegration-tests.skip=true -Dbuild.number=${targetVersion} clean package"
            }
          }
        }
    }
}
