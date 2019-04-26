node {
    stage('SCM Checkout') {
        git credentialsId: 'github', url: 'https://github.com/amrutarajiv/Movies-Microservice-Application'
    }

    stage('Docker compose run'){
        bat 'docker-compose up -d'
    }

}
