pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Display Jenkins URL and Build ID') {
            steps {
                echo "Jenkins URL: ${env.JENKINS_URL}"
                echo "Build ID: ${env.BUILD_ID}"
            }
        }
    }
}
