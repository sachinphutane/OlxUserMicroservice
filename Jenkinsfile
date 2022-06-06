pipeline {
    agent any

    stages {
         stage('Checkout') {
            steps {
                git 'https://github.com/mohammadazeez963/javaProject.git'
            }
         }
        stage('Compile') {
            steps {
                echo 'Compile'
            }
        }
         stage('Run') {
            steps {
                echo 'Run'
            }
         }
             stage('Test report using jecoco') {
            steps {
                echo 'jecoco'
            }
        }
             stage('Building docker image') {
            steps {
                echo 'image'
            }
        }
    }
}
