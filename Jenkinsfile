pipeline {
    agent { label 'MyNode' }
    stages {
        stage('Build') {
            steps {
                git branch: 'main', credentialsId: '5a7c9d41-962d-44ca-8a27-49348f8b6e59', url: 'https://github.com/garcin21/projet-maven.git'
            }
        }
    }
}