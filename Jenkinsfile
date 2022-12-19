pipeline {
    agent any
    stages {
        stage('SCMPull') {
            steps {
               git branch: 'main', url: 'https://github.com/rahul190292/jenkins_python_pipeline.git'
            }
        }
        stage('RunPython') {
            steps {
                bat 'python3 hello.py'
            }
        }
    }
}


