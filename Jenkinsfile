pipeline {
	agent {
		label {
				label 'ssh-slave1'
				customWorkspace "/home/ubuntu/jenkins_work"
				}
			}
			
	stages {
		
		stage("dir") {
			steps {
				echo "hello world"
				sh "mkdir dev5"
				}
			}
			
		stage("continuous-download") {
			steps {
				git credentialsId: '774', url: 'https://github.com/sachin93094/new_devops.git'
				sh "ls"
				}
			}
		}
	}
