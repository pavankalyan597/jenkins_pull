pipeline{
	agent any
	stages{
		stage('list'){
			steps{
				sh 'ls'
			}
		}
		stage('execute'){
			steps{
				sh 'python3 remote.py'
			}
		}
	}
}

