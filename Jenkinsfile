pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World i am new four"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
