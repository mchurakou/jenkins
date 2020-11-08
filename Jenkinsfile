pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build2') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}