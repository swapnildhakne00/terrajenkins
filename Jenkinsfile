pipeline{
  agent any
environment {
  PATH = "${PATH}"
}
stages{
    stage('terraform init'){
      steps{
        sh "terraform init"
      }
    }
   stage('terraform deploy'){
      steps{
        sh "terraform apply --auto-approve"
      }
  }
  }
}
