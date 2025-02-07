pipeline {
    agent any
 
    stages {
        stage('npm version check') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}

pipeline {
    agent any
     tools{
        nodejs 'NodeJS-22.6.0'
     }
    stages {
        stage('npm version check') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}