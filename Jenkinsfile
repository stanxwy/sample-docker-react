pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('pull code') {
            steps {
                echo 'staring......'
                git branch: 'main', url: 'https://github.com/stanxwy/sample-docker-react.git'
            }
        }
        stage('build') {
            steps {
                echo 'building......'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying......'
            }
        }
    }
}