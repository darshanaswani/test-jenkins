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
                sh 'npm install'
            }
        }

        stage('Build'){
            steps{
                echo 'Building the application...'
                sh 'npm run build'
            }
        }
}
}