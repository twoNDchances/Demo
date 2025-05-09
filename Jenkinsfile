pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                // echo 'Hello World'
                sh 'git log -1 HEAD --oneline'
                sh 'ls -la'
            }
        }
    }
}
