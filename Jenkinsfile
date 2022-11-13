pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }
       stage('execute') {
            steps {
                bat 'bzt Wiki2.yml -report'
            }
        }
    }
}
