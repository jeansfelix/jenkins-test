pipeline {
    agent {
        docker { image 'rhcircleci:11' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java -version'
            }
        }
    }
}
