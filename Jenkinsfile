node {
    stage('SCM Checkout') {
        git credentialsId: 'github', url: 'https://github.com/amrutarajiv/Movies-Microservice-Application'
    }

    stage('Docker compose build'){
        bat 'docker-compose build'
    }

    stage('Docker compose run'){
        bat 'docker-compose up -d'
    }

}
