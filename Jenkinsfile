// node {
// 	stage('Cleanup Workspace') {
//         echo "Testing testing ... !"
//     }
// }

pipeline {
    agent any
    parameters {
        string(name: 'commitId', defaultValue: 'default-commit-id', description: 'Blah')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello There ! ${params.commitId}"
            }
        }
    }
}