pipeline {
    agent {
        docker { image 'node:16-alpine' }
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'node --version'
            }
        }
    }
}
