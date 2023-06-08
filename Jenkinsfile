pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello.java'
            }
        }
    }
}