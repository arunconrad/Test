pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is the first build'
            }
        }
		stage('Code review') {
            steps {
                echo 'This is the first code review step'
            }
        }
		stage('Test') {
            steps {
                echo 'This is the first Test step'
            }
        }
		stage('Deploy') {
            steps {
                 script {
            if (!fileExists('/var/lib/jenkins/workspace/pipelineproj2/Jenkinsfile')) {
                echo "File /var/lib/jenkins/workspace/pipelineproj2/Jenkinsfile found!"
	    
            }
		}
           		
            }
        }
		stage('Delivery') {
            steps {
                echo 'This is the first Delivery step'
            }
        }
		stage('Monitor') {
            steps {
                echo 'This is my first pipeline syntax setup'
		fileExists '/var/lib/jenkins/workspace/pipelineproj2/Jenkinfile'
            }
        }
    }
}
