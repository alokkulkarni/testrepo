pipeline {
    agent any
    stages {
        stage('hello') {
            steps {
                sh "JCasC env.hello: ${env.hello}"
            }
        }
    }
}
