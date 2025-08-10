    pipeline {
    agent any

    tools {
        maven 'rihanmaven' 
    }

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Rihan297/Clone_Build_rihan.git'
            }
        }

        stage('Build maven Code') 
        {
            steps {
                sh 'mvn package'
            }
        }
    }
}
