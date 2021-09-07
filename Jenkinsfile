pipeline {
    agent any

    stages {
        stage('SCM Checkout') {
            steps {
                echo 'This step is checking out your SCM Account'
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/Jaypalsolanki123/Python-Demo']]])
        }
    }
}

