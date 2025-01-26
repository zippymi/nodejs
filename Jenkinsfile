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
         stage('Run Python Script') {
            steps {
                sh 'python hello.py' 
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World' 
            }
        }
    }
}
