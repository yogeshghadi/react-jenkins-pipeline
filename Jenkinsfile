pipeline {
    // agent any

    // tools {nodejs "node12"}
    agent  {
        docker {
            image 'node:14-alpine'
        }
    }

    stages {
        stage('Build') { 
            steps {
                sh 'node -v'
            }
        }
    }
}