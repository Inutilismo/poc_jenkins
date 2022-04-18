pipeline {
    agent { docker { image 'php:8.1.0-alpine' } }
    options { 
      retry(3) 
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
