pipeline {
  agent any
  stages {
    stage('Déploiement') {
      steps {
        sh '/usr/bin/ansible-playbook -i inventory.ini playbook.yml'
      }
    }
  }
}
