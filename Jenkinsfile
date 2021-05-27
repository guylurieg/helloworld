pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'cd /root/sample-project'
                sh 'mvn --version'
                sh 'mvn clean package'
            }
        }
    }
}
