pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Simulate a build by creating a file
                sh 'echo "Building project..." > build.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulate tests by creating another file
                sh 'echo "Running tests..." > test.txt'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to development environment...'
                // Simulate deployment by moving files to a deploy directory
                sh '''
                    mkdir -p deploy
                    cp build.txt test.txt deploy/
                    echo "Deployment completed."
                '''
            }
        }
    }
}
