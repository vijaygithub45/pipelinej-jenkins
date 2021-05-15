pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Build Step'
                sh 'mvn --version'
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
