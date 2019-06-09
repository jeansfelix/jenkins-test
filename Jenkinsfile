pipeline {
    agent {
        docker { image 'galeb/rhcircleci:11' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java -version'
            }
        }
    }
}
