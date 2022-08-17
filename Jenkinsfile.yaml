pipeline{
    agent {
      docker { image 'audrinhbs/live-ci-cd:latest'}
    }

    stages{
      stage('Test'){
        steps {
          sh 'go version'
        }
    }
}