pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                shell 'echo "Hello World"'
                shell '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
