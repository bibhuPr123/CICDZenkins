pipeline{
	agent any
	stages{
		stage('one'){
			steps{
				echo 'Hi,  hello world from zenkins : step1'
			}
		}
		stage('two'){
			steps{
				echo 'Hi,  hello world from zenkins : step2'
			}
		}
		stage('three'){
			steps{
				input('Do you want to proceed?')
				echo 'Hi,  hello world from zenkins : step3'
			}
		}
		stage('four'){
			steps{
				echo 'Hi,  hello world from zenkins : step4'
			}
		}
	}
}