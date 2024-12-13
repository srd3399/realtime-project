properties([
    parameters([
        choice(
            choices: ['PRD', 'RELEASE', 'TEST'], 
            name: 'ENV'
        ),
        choice(
            choices: ['plan', 'apply', 'destroy'], 
            name: 'Terraform_Action'
        )])
])

pipeline {
    agent any
    stages {
        stage('Preparing') {
            steps {
                sh 'echo Preparing'
            }
        }    
    }
}        