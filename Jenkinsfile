pipeline {
    agent any 
    stages {
        stage('checkout') {
	     steps {
	        sh 'ls'
                sh 'ls -altr'
	     }
	}
	stage('Run script') {
	     steps {
	        sh 'python str.py'
		sh 'python typecast.py'
	     }
	}
    }
}
