pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Step 1: Initializing build process"'
                bat 'echo "Step 2: Running pre-build checks"'
                bat '''
                    echo "Step 3: Compiling source code"
                    echo "Step 4: Build completed successfully"
                '''
            }
        }
    }
}
