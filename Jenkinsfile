pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage(‘clone-code’) {
            steps {
               git branch: 'main', url: 'https://github.com/easycloudcompute/tweet-trend-new.git'
            }
        }
    }
}
