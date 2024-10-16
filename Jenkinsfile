pipeline {
    agent any // Use any available agent
    stages {
        stage('Checkout') {
            steps {
                // Check out the code from the repository
                checkout scm
            }
        }
        stage('Run Hello World') {
            steps {
                // Print "Hello, World!" and run the Python script
                echo 'Running Hello, World script...'
                bat 'python hello.py' // Use 'bat' for Windows commands
            }
        }
    }
}
