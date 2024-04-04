pipeline{
    agent {
        docker {
            image 'node:20-alpine'
        }
    }
    stages{
        stage('Install'){
            steps{
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