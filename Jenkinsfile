pipeline {

    agent any
    stages{

        stage("compile"){

            steps{
                bat 'javac Demo.java'
            }
        }

        stage("run"){

            steps{
                bat 'java Demo'
            }
        }
    }
    }
