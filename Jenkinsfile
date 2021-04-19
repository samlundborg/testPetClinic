
pipeline {
    agent any
    stages {
        stage('First Checkout') {
            steps {
                git 'https://github.com/Kakan44/spring-petclinic-rest.git'
            }
        }
        stage('Second Checkout') {
            steps {
                git 'https://github.com/Flaecken/spring-petclinic-angular.git'
            }
        }
        stage('First Build') {
            steps {
                sh('. spring-petclinic-rest/build.sh')
            }
        }
        stage('Second Build') {
            steps {
                sh('. spring-petclinic-angular/build.sh')
            }        
        } 
    }
}
