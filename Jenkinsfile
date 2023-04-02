
pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                dir('C:/Users/Zaynab/Desktop/test/test code/SelenTest.java'){ 
                    bat 'java -m Junit -v'
                }
            }
        }
        stage('Clean Workspace'){
            steps {
                cleanWs()
            }
        }
    }
}

