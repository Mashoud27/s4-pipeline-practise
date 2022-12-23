pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls
                pwd
                uname -r
                touch paul
                pwd
                '''
            }
        }
    }
}

