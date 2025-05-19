@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Before calling shared lib'
                helloworld()
                echo 'After calling shared lib'
            }
        }
    }
}
