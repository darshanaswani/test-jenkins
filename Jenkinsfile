pipeline{
    agent {
        docker {
            image 'node:18.16.0-alpine'
        }
    }
    stages{
        stage('Install'){
            steps{
                sh 'ls'
                echo 'Installing dependencies...'
                sh 'node --version'
                sh 'npm --version'
                sh 'ls'
             
            }
        }


}
}