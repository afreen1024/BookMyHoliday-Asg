pipeline {

  agent any
  stages {
    stage('Build') {
      steps {
            bat 'mvn -DskipMunitTests deploy -DmuleDeploy'
      }
    }
}

}  