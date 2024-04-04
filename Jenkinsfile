pipeline{
    agent {
        docker {
            image 'node:18.16.0'
        }
    }
    stages{
        stage('Install'){
            steps{
                echo 'Installing dependencies...'
                sh 'npm install --legacy-peer-deps'
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