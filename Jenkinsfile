pipeline {
    agent any

    stages {
        stage('linter') {
            steps {
                sh '.eslintrc.json'
            }
        }
        stage('test') {
            steps {
                sh 'sum.test.js'
            }
        }
    }
}