pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls
                pwd
                touch file1
                pwd
                '''
            }
        }
    }
}

