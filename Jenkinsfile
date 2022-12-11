pipeline {
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                chmod 755 hello.sh
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                ls /bin/sh
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                ./hello.sh
                '''
            }
        }
    }
}
