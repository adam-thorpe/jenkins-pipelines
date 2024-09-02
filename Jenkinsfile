pipeline {
    agent any
    parameters {
        string(name: 'commitId', defaultValue: 'default-commit-id')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello There ! ${params.commitId}"
            }
        }
    }
}