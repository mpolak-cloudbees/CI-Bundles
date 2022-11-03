// Uses Declarative syntax to run commands inside a container.
pipeline {
    agent {
        kubernetes {

        }
    }
    stages {
        stage('Main') {
            steps {
                sh 'echo Hello: World' 
                sh 'curl -k https://flow.cloudbees.guru/flow'
            }
        }

    }
}
