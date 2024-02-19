  pipeline {
    agent any
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Manjusiddapur12/mavenb17.git'
            }
        }
        
        stage('mvn clean') {
            steps {
                sh 'mvn clean package'
            }
        }
        

    }
}
