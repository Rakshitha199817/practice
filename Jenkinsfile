pipeline {
    agent any
    stages {
        
        stage('git'){
            steps{
                git 'https://github.com/Rakshitha199817/practice.git'
            }
        }
        stage('Build') {
            steps {
               sh "mvn clean package"
            }
    
        }
    }
}
