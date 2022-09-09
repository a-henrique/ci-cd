pipeline {
    agent any

    stages {

        stage ('step-1') {
            steps {
                sh 'wget https://google.com'
            }
        }
        stage ('step-2') {
            steps {
                sh 'cat index.html'
            }
        }
        stage ('step-3') {
            steps {
                echo "Este é o step 3 da minha esteira de dev com jenkins"
            }
        }
    }
}