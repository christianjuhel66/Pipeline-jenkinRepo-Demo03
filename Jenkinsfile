pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Etape de build v2"
				sh 'python --version'
			}
		}
		stage('Tests') {
			steps { 
				echo "Etape de test"
			}
		}
		stage ('Deploy') {
			steps {
				echo "Etape de déploiement"
			}
		}
	}
}
