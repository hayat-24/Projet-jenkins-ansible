pipeline {
    agent any
    environment {
        PATH = "/usr/bin:$PATH"
    }
    stages {
        stage('Déploiement') {
            steps {
                sh 'ansible-playbook -i inventory.ini playbook.yml'
            }
        }
    }
}
