pipeline {
	agent any
	stages {
		stage('Test'){
			steps {
				sh './scripts/test.sh'
			}
		}
		stage('Build'){
			steps{
				sh './scripts/build.sh'
			}
		}
		stage('Push'){
			steps{
				sh './scrtips/push.sh'
			}
				
		}
	
	}
}

