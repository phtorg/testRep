pipeline {
    agent { docker { image 'maven:3.3.3' }
        label 'docker'}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}