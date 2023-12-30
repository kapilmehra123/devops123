pipeline {
    agent any
    environment {
      PATH = "$PATH:/opt/apache-maven-3.6.3/bin"
    }
    
    stages {

        stage('CLEAN WORKSPACE') {
            steps {
                cleanWs()
            }
        }

        stage('CODE CHECKOUT') {
            steps {
                git 'https://github.com/kapilmehra123/devops123.git'
            }
        }

    }
}      
