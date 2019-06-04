pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withAnt(installation: 'Ant') {
                        bat "ant build"
                }
            }
        }
    }
}
