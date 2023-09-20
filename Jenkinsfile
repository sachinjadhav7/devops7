pipeline {
	agent {
		label {
				label 'ssh-slave1'
				customWorkspace "/home/ubuntu/jenkins_work"
				}
			}
			
			environment {
							Name = "pavan"
							PROF = "devops"
							BATCH = "july"
			
			
			
			
	stages {
		
		stage("env") {
			steps {
				echo "hello world"
				echo "${Name}"
				echo "${PROF}"
				echo "${BATCH}"
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
