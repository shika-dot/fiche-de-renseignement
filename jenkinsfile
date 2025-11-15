pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git url: 'https://github.com/shika-dot/fiche-de-renseignement.git', branch: 'main'
            }
        }

        stage('Test HTML/CSS') {
            steps {
                sh 'echo "Pipeline OK pour HTML/CSS !"'
            }
        }
    }
}
