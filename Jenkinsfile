pipeline {
    agent any
    stages{
        stage('clone the repo'){
          steps{
              git 'https://github.com/geeselearnings/masterpiece000.git'
          }  
        }
        stage('build'){
            steps{
                sh 'pwd'
                sh 'mvn clean compile'
            }
        }
        stage('test'){
            steps{
                sh 'mvn test'
            }
        }
        stage('install'){
            steps{
                sh 'mvn install'
            
        }
    }
}
}
