pipeline {
        agent any
        stages {
            stage('deploy') {
                steps {
                    sh 'kubectl apply -f .'
                }
            }
        }
}