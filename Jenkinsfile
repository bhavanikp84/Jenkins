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

        stage('jenkins') {
            steps {
                echo 'Hello Jenkins'
                echo 'How are you doing!!'
                sh 'date'
                sh 'sleep 30'
            }
        }
    }
}
