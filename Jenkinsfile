pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                // Use sh for Linux or bat for Windows
                chmod +x scripts/hello.sh
                sh './scripts/hello.sh'
            }
        }
    }
}
