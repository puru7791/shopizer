pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                git 'https://github.com/puru7791/shopizer.git'
                sh 'mvn clean package'
            }
        }
    }
}