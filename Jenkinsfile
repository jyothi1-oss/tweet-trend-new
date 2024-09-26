pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code from git') {
            steps {
                git branch: 'main', url: 'https://github.com/jyothi1-oss/tweet-trend-new.git'
            }
        }
    }
}
