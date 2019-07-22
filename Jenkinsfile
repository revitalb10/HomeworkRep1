pipeline {
    agent any
    stages {
        stage('File Creation') {
            steps {
                bat 'echo Revital Ben-Gigi > C:\\Users\\Revital\\Desktop\\Homework1\\MyName.txt'
            }
        }
        stage('Print text file') {
            steps {
                bat 'type C:\\Users\\Revital\\Desktop\\HomeWork1\\MyName.txt'
            }
        }
       stage('Print Free Space') {
            steps {
               git 'https://github.com/revitalb10/HomeworkRep1.git'
            }
        }
       stage('Build') {
            steps {
               bat 'python Homework.py'
            }
        }      
    }
}
