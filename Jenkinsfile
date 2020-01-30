@Library('jenkins_shared_library@master') _

pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/dp119/atmosphere2.git"
            )
            }
    }
    }
}