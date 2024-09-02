pipeline {

    // agent {
    //     node {
    //         label 'agent-01'
    //     }
    // }

    options {
        buildDiscarder logRotator( 
            daysToKeepStr: '16', 
            numToKeepStr: '10'
        )
    }

    stages {
        
        stage('Cleanup Workspace') {
            steps {
                sh """
                echo "Testing testing ... !"
                """
            }
        }

    }   
}