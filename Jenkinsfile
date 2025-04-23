pipeline {
    agent any

    tools {
        nodejs 'NodeJS 23.11.0'   // <- Must match EXACTLY the NodeJS installer name you added in Jenkins
    }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
