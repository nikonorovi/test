pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'touch hello-world-file'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
