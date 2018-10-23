pipeline {
  agent any
  stages {
    stage ('***clean***') {
      steps {
        sh "mvn clean"
      }
    }
    stage ('***Build***') {
      steps {
        sh "mvn test"
      }
    }
    stage ('***Deploy***') {
      steps {
        sh "mvn package"
      }
    }
    stage ('****Display Messages****'){
      steps {
        echo "feature branch success 2nd times......!"
       }
    }
  }
}
