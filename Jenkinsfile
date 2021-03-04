pipeline {
    agent any
    stages {
		stage('Check out repo') {
			steps{
				sh 'echo "getting repo updates"'
			}
		}
        stage('Build') {
            steps{
                sh 'echo "Hello world!"'
            }
        }
		stage('Upload artifact'){
			steps{
				sh 'echo "subiendo artefacto"'
			}
		}
    }
}
