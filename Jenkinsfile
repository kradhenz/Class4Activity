pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'cad7ff8c-e2b1-4e21-bbf7-0f20bf7e6678', url: 'https://github.com/kradhenz/MyProject.git'
            }
        }
    }
}