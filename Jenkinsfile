Jenkinsfile (Scripted Pipeline)
/* Requires the Docker Pipeline plugin */
node('docker') {
    checkout scm
    stage('Build stage ...') {
        docker.image('ruby').inside {
            sh 'ruby --version'
        }
    }
}
