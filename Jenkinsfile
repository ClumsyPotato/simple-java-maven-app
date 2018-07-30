pipeline {
    agent any

    stages {
	stage('Build') {
	    steps {
		echo 'Building..'
		sh 'mvn package -Dmaven.test.skip=true'
	    }
	}
	stage('Test'){
	    steps {
		echo 'Testing..'
	    }
	}
    }
}
