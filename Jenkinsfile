pipeline {
    agent any

    stages {
        stage('linter') {
            steps {
                sh '.elintrc.json'
            }
        }
        stage('test') {
            steps {
                sh 'sum.test.js'
            }
        }
    }
}