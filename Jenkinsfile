pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                dir('sample-project') {
                  sh 'mvn --version'
                  sh 'mvn clean package'
                }
            }
        }
    }
}
