pipeline {
    agent any

    tools {nodejs "node12"}
    /* {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 3000:3000' 
        }
    } */
    stages {
        stage('Build') { 
            steps {
                sh 'npm build' 
            }
        }
    }
}