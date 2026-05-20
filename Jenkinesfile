pipeline {
    agent any

    stages {

        stage('checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/riyaa-devops/sinci.git'
            }
        }

        stage('build') {
            steps {
                echo "building"
            }
        }

        stage('test') {
            steps {
                echo "testing"
            }
        }
    }
}
