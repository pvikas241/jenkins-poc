@Library("my-shared-lib") _

pipeline {
    agent any
    parameters {
        choice(name: 'StageToRun', choices: ['None', 'HelloWorld', 'HiWorld'], description: 'Select a stage to run')
    }
    stages {
        stage('Execute Shared Library') {
            steps {
                script {
                    servicedomainlibrary(params.StageToRun)  // Call the shared library function
                }
            }
        }
    }
}
