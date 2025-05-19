@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Before calling shared lib'
                helloWorld()
                echo 'After calling shared lib'
            }
        }
    }
}
