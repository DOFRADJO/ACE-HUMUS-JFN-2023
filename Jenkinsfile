pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    // The following command will clone your repository and check out the master branch by default.
                    git credentialsId: 'jenkins-user-github', url: 'https://github.com/anderson-metsanou/Git-basics.git'
                    // You can use 'ls -lart' to view all the files that have been cloned.
                }
            }
        }
    }
}
