stage('Build') {
    steps {
        // Install dependencies using pip
        sh 'pip install -r requirements.txt'
        
        // Run linting checks with flake8
        sh 'flake8 .'
    }
}
