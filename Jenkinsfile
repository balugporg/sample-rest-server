pipeline {
    agent none
    stages {
        stage('Publish Event') {
            steps {
                publishEvent(generic('beeEvent'))
            }
        }
    }
}
