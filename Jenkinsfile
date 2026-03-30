pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                // Ensure the script is executable first
                sh 'chmod +x scripts/hello.sh'
                
                // Then execute it
                sh './scripts/hello.sh'
            }
        }
    }
}
