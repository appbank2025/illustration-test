pipeline{
	agent any
	stages{
		stage('1-clone the repo'){
			steps{
				sh 'action1'
			}
		}
		stage('2-move the repo'){
			steps{
				sh 'action2'
				sh 'action2b'
			}
		}
		stage('3-build the repo'){
			steps{
				sh 'pwd'
				sh 'action3'
			}
		}
	}
}
