chmod +x scripts/hello.sh
pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                // Use sh for Linux or bat for Windows
                sh './scripts/hello.sh'
            }
        }
    }
}
