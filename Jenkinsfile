pipeline {
    agent any
    tools {
        nodejs 'NodeJS 23.11.0'  // <-- this must match exactly the name you gave!
    }
    stages {
        stage('Print Node Version') {
            steps {
                sh 'node -v'
            }
        }
    }
}
