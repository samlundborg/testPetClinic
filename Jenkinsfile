node {
    dir('RepoOne') {
        git url: 'https://github.com/somewhere/RepoOne.git'
    }
    dir('RepoTwo') {
        git url: 'https://github.com/somewhere/RepoTwo.git'
    }

    sh('. RepoOne/build.sh')
    sh('. RepoTwo/build.sh')
}
