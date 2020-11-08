pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build4') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}