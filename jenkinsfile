pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Display JENKINS_URL and BUILD_ID') {
            steps {
                git 'https://github.com/The-indigo/maven3.git'
                sh 'echo JENKINS_URL: $JENKINS_URL'
                sh 'echo BUILD_ID: $BUILD_ID'
            }
        }
    }
}