
pipeline {
    agent any
    node {
        dir('RepoOne') {
            git url: 'https://github.com/Kakan44/spring-petclinic-rest.git'
        }
        dir('RepoTwo') {
            git url: 'https://github.com/Flaecken/spring-petclinic-angular.git'
        }

        sh('. spring-petclinic-rest/build.sh')
        sh('. spring-petclinic-angular/build.sh')
    }
}
