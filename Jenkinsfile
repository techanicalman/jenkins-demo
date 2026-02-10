
pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Webhook triggered Jenkins!'
            }
        }

        stage('Done') {
            steps {
                echo 'Pipeline completed 🎉'
            }
        }
    }
}
