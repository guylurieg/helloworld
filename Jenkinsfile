pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'cd sample-project'
                sh 'mvn --version'
                sh 'mvn clean package'
            }
        }
    }
}
