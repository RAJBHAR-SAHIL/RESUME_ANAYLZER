pipeline {
    agent any
    stages{
        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "D:/Coding Software/xampp/htdocs/exp4" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
