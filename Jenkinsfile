Jenkinsfile (Declarative Pipeline)

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'mkdir output'
                sh 'cd output'
                sh 'cat info.txt'
            }
        }
    }
}
