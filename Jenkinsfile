pipeline {
    agent any
    tools {
        gradle "jenkins_gradle"
    }
    stages {
        stage('Gradle') {
            steps {
                sh 'gradle --version'
            }
        }
    }
}
