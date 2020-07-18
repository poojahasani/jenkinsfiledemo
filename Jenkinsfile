pipeline {
    agent any
    tools {
        maven 'M2_HOME'
       
    }

 

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('git checkout'){
            steps {
                git credentialsId: 'GIT_Cred', url: 'https://github.com/poojahasani/jenkinsfiledemo.git'
            }
        }

