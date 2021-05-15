pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Build Step'
                bat 'mvn --version'
            }
        }
        stage('test') {
            steps {
                echo 'Tests'
                sh 'pwd'
            }
        }
        stage('deploy') {
            steps {
                echo "deploy step"
            }
        }
    }
}
