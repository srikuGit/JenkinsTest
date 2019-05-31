pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withAnt() {
                        "ant main"
                }
            }
        }
    }
}
