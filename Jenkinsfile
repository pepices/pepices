pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/var/jenkins_home/juan/juan.sh'
                sh '''
                    echo "Varias órdenes en un step chuta tb. Kaka de la vaca"
                    ls -lah
                '''
                sh '''
                    echo "coponss bendito..."
                '''
            }
        }
    }
}
