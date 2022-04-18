pipeline {
    agent { any { image 'php:8.1.0-alpine' } }
    options { 
      retry(5) 
    }
    stages {
        stage('build') {
            steps {
                fileExists 'kkk'
                sh 'php --version'
            }
        }
    }
}
