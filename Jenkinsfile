pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/var/jenkins_home/juan/juan.sh'
                sh '''
                    echo "Varias órdenes en un step chuta tb."
                    ls -lah
                '''
                sh '''
                    echo "copon bendito..."
                '''
            }
        }
    }
}
