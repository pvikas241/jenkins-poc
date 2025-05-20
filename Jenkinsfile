@Library("my-shared-lib") _

pipeline {
    agent any
    stages {
        stage('Execute Shared Library') {
            steps {
                script {
                    servicedomainlibrary()  // Call the shared library function without parameters
                }
            }
        }
    }
}
