pipeline {
    agent any

    tools {
        jdk 'JDK11'
        git 'Default'
    }

    stages {
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
