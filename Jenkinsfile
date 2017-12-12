pipeline{
  agent any

stages{
      stage("First Teswert"){
    steps{
    git credentialsId: 'git', url: 'https://github.com/tim-steffen/ansibleTemplateTest'
    }
  }
 stage("First Tesewert"){
    steps{
    sh 'ls'
    }
  }
  stage("First Test"){
    steps{
    ansiblePlaybook  extras: '--vault-password-file passwordFile --extra-vars="host_group=mycomputer environ=Dev"', inventory: 'host', playbook: 'sample.yml', sudoUser: null
    }
  }
}
}
