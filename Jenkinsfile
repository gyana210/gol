pipeline{
    agent {label 'MASTER'}
    stages {
        stage('source'){
            step{
                git 'https://github.com/gyana210/gol.git'
            }
        }
        stage('build'){
            step{
                sh 'mvn package'
            }
        }
    }
}
