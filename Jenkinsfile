pipeline{
	agent any
	stages{
		stage('1-clone the repo'){
			steps{
				sh 'lsblk'
			}
		}
		stage('2-move the repo'){
			steps{
				sh 'lscpu'
				sh 'hostname'
			}
		}
		stage('3-build the repo'){
			steps{
				sh 'pwd'
			}
		}
		stage('4-syscehck'){
			steps{
				sh 'free -h'
				sh 'free -g'
				sh 'cat /etc/os-release'
			}
		}
	}
}
