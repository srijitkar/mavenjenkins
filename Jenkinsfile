pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
		
		stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
		
		stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
	
	post{
	
	always {
	emailext body: '''Hi,

Please find the status report.

Regards,
Admin''', subject: 'Status Report', to: 'swarnva123k@gmail.com'
	}
	}
}
