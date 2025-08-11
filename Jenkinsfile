pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\\Users\\RELIANCE\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" --version'
            }
        }
        stage('hello') {
            steps {
                bat '"C:\\Users\\RELIANCE\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" manage.py'
            }
        }
    }
}
