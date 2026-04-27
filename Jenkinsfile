pipeline {
    agent any

    stages {
        stage('Checkout the SCM') {
            steps {
                git branch: "main", url: 'https://github.com/Sangamesh080/Jenkins_Demo.git'
            }
        }
        stage('Execution') {
            steps {
                sh 'python3 add.py'
            }
        }
    }
}
