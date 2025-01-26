pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git branch: 'main', 
                    credentialsId: 'your-credentials-id', 
                    url: 'your-repository-url'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World' 
            }
        }
    }
}
