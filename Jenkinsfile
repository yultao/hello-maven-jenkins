pipeline {
    agent any
    tools {
        maven 'apache-maven-3.8.6'
        jdk 'jdk-17.0.5'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean package'
            }
        }
//         stage('Test') {
//             steps {
//                 //
//             }
//         }
//         stage('Deploy') {
//             steps {
//                 //
//             }
//         }
    }
}