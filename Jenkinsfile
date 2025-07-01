pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
    }

    stages {
        stage('Build') {
            steps {
                echo "Flag: ${params.userFlag}"
            }
        }
        stage('Release') {
            steps {
                echo "Hello Release"
            }
        }
    }
}
