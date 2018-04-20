pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                sh 'echo building;sleep 10;echo built' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo testing;sleep 15;echo tested'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo deploying;sleep 15;echo deployed'
            }
        }
    }
}