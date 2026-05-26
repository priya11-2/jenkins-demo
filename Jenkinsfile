@Library('mylib') _

pipeline {

    agent any

    stages {

        stage('Build') {
            steps {
                script {
                    buildApp()
                }
            }
        }
    }
}
