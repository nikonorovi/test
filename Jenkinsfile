pipeline {
stage('Setting the variables values') {
    steps {
         sh '''
            #!/bin/bash
            echo "hello world"
         '''
    }
  post {
    always {
      cleanWs()
    }
  }
}
