pipeline {
  agent any
  stages {
    stage('Déploiement') {
      steps {
        sh 'ansible-playbook -i inventory.ini playbook.yml'
      }
    }
  }
}
