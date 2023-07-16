pipeline {
    agent any

    stages {
        stage('Prod') {
            steps {
                echo 'Hello Prod-stage'
                build quietPeriod: 5, job: 'stackfusion'
            }
        }
    }
}
