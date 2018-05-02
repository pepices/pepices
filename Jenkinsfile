pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/var/jenkins_home/juan/juan.sh'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh '''
                    echo "copon bendito 123"
                '''
            }
        }
    }
}
