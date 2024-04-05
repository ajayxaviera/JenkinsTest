pipeline {
    agent any

    tools {
        jdk 'JDK11'
        git 'Default'
    }

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/ajayxaviera/JenkinsTest.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Test.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Test'
            }
        }
    }
}
