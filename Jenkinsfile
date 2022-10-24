pipeline {
    agent any
    tools {
        maven 'Maven 3.8.6'
        jdk 'jdk8'
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