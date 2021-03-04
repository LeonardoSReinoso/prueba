pipeline {
    agent any
    stages {
		stage('Check out repo') {
			steps{
				sh 'mkdir -p Module1'
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
