pipeline {
    agent {
        node {
            label 'maven-agent'
        }
    }

    stages {
        stage('Clone code') {
            steps {
                git 'https://github.com/sateesh-akula/testPro.git'
            }
        }
    }
}
