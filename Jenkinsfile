pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
                  ansiblePlaybook credentialsId: 'ssh-p', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
