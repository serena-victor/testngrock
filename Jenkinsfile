pipeline {
	agent any  

	stages {
		stage('Build Docker') {
			steps {
				bat 'docker compose down'
				bat 'docker compose up -d'
			}
		}
	}
}