pipeline {
    agent any


    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Insert your build commands here (e.g., shell scripts, Maven commands, etc.)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Insert your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Insert your deployment commands here
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
