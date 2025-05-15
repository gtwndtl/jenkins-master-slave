pipeline {
    agent { label 'slave-01' }

    stages {
        stage('Test') {
            steps {
                echo "Running on agent: ${env.NODE_NAME}"
                sh 'hostname'
                sh 'whoami'
                sh 'uname -a'
            }
        }
    }
}
