pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git branch: 'main', 
                    credentialsId: 'Zippymi', 
                    url: 'https://github.com/zippymi/nodejs'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World' 
            }
        }
    }
}
