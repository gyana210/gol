pipeline{
    agent {label 'MASTER'}
    stages {
        stage('source'){
            steps {
                git 'https://github.com/gyana210/gol.git'
            }
        }
        stage('build'){
            steps {
                sh 'mvn package'
            }
        }
    }
}
