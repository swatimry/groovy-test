pipeline {
    agent any
    stages {
        stage('Breakfast') {
            steps {
                echo "I am having breakfast"
            }
        }
        stage('Workout') {
            steps {
                echo "I am doing workout"
            }
        }
        stage('Study') {
            steps {
                echo "I am studying"
            }
        }
        stage('Familytime') {
            steps {
                echo "I am spending time with my family"
            }
        }
        stage('Play') {
            steps {
                echo "I am playing"
            }
        }
    }
    post {
        success {
            echo "My day went well"
        }
        failure {
            echo "Bad luck today, day did not go well!!!"
        }
    }
}
