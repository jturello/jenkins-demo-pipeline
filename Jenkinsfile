pipeline {
    agent { docker { image 'node:10.15.1-alpine' } }
    stages {
        stage('build') {
	    steps {
	        sh 'npm --version'
	    }
	}
    }
}
