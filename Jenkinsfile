pipeline {
    
    agent any  

    environment {
        REGISTRY_URL = 'https://registry.mydomain.com'
    }   

    stages {

        stage('Init'){
            steps {
                echo 'Init'
                echo '******************************'
                echo "registry url : ${env.REGISTRY_URL}"
            }
        }

        stage('Yarn Install') {
            steps {
                echo 'Yarn Install'
                echo '******************************'
            }
        }

        stage('Yarn Build') {
            steps {
                echo 'Yarn Build'
                echo '******************************'
            }
        }

        stage('Deploy') {
            steps{
                echo 'Deploy'
                echo '******************************'
            }
        }
    }
}