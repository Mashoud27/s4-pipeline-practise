pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls
                pwd
                touch file1
                uname -r
                touch paul
                pwd
                '''
            }
        }
    }
}

