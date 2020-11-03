pipeline {
    agent any
    tools {
        maven 'Maven3'
        jdk 'jdk1.8'
        terraform 'terraform'
    }
    stages {
         stage('Maven version') {
            steps {
            sh 'mvn verify'
            }
           }
        stage('Terraform version') {
            steps {
            sh 'terraform version'
            }
           }
           
       }
       }
