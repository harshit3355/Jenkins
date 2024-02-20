pipeline{
    agent any
    tools{
        maven ='MAVEN_HOME'
    }
    stages{
        stage('Initiaization'){
            steps{
                echo 'First Stage of the pipeline'
            }
        }
        stage('Clean Stage'){
            steps{
                bat 'mvn clean'
            }
        }
        stage('Install Stage'){
            steps{
                bat 'mvn install'
            }
        }
        stage('Success Stage'){
            steps{
                echo 'Successfully Built'
            }
        }
    }
}