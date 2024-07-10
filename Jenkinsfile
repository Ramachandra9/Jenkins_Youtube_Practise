pipeline {
	agent any
	tools {
		jdk 'jdk17'
		nodejs 'node16'
	}
    stages {
        stage('clean workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Checkout from Git') {
            steps {
                git branch: 'main', url: 'https://github.com/Ramachandra9/Jenkins_Youtube_Practise'
            }
        }
    }
}
