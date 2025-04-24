pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/SEONJOO-JANG/kosta-demo.git'
                sh "mvn clean package"
            }
        }
    }
}
