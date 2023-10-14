pipeline {
    agent {
        docker {
            image 'node:16-alpine'
        }
    }

    stages {
        stage('Build') {
            steps {
                // Install Node.js dependencies using npm
                sh 'npm install --save'
            }
        }
    }
}

