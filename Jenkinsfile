pipeline {
    agent any

    stages {

        stage('Build Image') {
            steps {
                sh 'docker build -t jenkins-demo .'
            }
        }

        stage('Remove Container') {
            steps {
                sh 'docker rm -f mycontainer || true'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d -p 8082:80 --name mycontainer jenkins-demo'
            }
        }
    }
}
