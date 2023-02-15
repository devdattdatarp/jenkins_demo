pipeline {
agent any
    stages {
        stage('Clone Git') {
            steps {
                git 'https://github.com/devdattdatarp/jenkins_demo.git'
                    }
                }
        stage('Build Code') {
            steps {
                    echo "Hello"
                    sh "chmod u+x a.out"
                    sh "./a.out"
                    }
                }
        
            }
}
