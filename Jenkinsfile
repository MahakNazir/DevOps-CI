pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from GitHub
                git url: 'git@github.com:MahakNazir/DevOps-CI.git'
            }
        }
        stage('Build') {
            steps {
                // Compile Java code
                sh 'javac GreetMahak.java'
            }
        }
        stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java GreetMahak'
            }
        }
    }
}
