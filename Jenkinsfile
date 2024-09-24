pipeline {
    agent any
    stages {
        stage('Test Artifactory Connection') {
            steps {
                script {
                    def server = Artifactory.server('Your-Artifactory-Server-ID')
                    server.connectionCheck()
                }
            }
        }
    }
}
