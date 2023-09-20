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
				sh "mkdir dev"
				}
			}
		}
	}
