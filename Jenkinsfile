pipeline {
    agent seb-label

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/domfellner/dummy-project.git'
                echo 'Hello World'
            }
        }
    }
}
