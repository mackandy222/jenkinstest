import groovy.json.JsonSlurper

branchName="mytestbranchname"
jetID="mytestjetid"

echo "Pipeline execution"

def deployasdraft() {
    echo "fdftest"
}


pipeline {
    agent any


    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Insert your build commands here (e.g., shell scripts, Maven commands, etc.)
            }
        }

        stage('Testrest') {
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
            echo 'Pipeline completed successfully! and this is my hello yest yes yess '
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
