pipeline {
    agent any

    environment {
        PATH = "/opt/maven/bin:$PATH"
    }

    stages {
        stage('Git Clone') {
            steps {
                git url: 'https://github.com/NileshDamodare/sparkjava-war-example.git'
                
            }
        }
}
}
