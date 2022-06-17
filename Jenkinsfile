pipeline {
    agent any {
        environment {
  environment  = "019523160407.dkr.ecr.ap-south-1.amazonaws.com/htmlpage"
}
stages {
    stage ( 'Git checkout ')
    step {
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'git@github.com:rsaideekshith/htmlrepo.git']]])
    }
}
    }
}