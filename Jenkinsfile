pipeline {
    agent any

    stages {

        stage('Clone Repo') {
            steps {
                echo "Repository cloned successfully"
            }
        }

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Print HTML') {
            steps {
                bat 'type index.html'
            }
        }

    }
}
