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
                    sh "chmod u+x Prog1.py"
                    sh "./a.c"
                    }
                }
        
            }
}
