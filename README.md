pipeline {
    agent any
    stages {
        stage ("Welcome") {
            steps {
                echo "Welcome to the home"
            }
        }
    }
}
