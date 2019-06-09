pipeline {
    agent {
        docker { image 'node:rhcircleci' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java -version'
            }
        }
    }
}
