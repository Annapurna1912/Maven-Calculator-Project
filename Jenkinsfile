pipeline {
  agent any

  stages {
    stage( 'Checkout') {
      git
  'http://github.com/Annapurna1912/Maven-Calculator-Project.git'
    }
  }
     stage('Build') {
       steps {
         sh 'mvn clean package'
       }
     }
}
}
