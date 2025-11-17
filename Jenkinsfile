pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        git url: 'github.com:shika-dot/fiche-de-renseignement.git', branch: 'main'
      }
    }

    stage('Tests') {
      steps {
        sh 'echo "Tests en cours..."'
      }
    }

    stage('Build Docker') {
      steps {
        sh 'echo "Construction de l\'image Docker..."'
      }
    }

    stage('Deploy to Server') {
      steps {
        sh 'echo "Déploiement sur le serveur..."'
      }
    }
  }
}

