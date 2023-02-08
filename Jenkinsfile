pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Clone') {
            steps {
                sh 'git clone https://github.com/chetanborade/demorepo.git'
            }
        }
    }
}
