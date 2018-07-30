pipeline {
    agent any

    stages {
	stage('Build') {
	    steps {
		echo 'Building..'
		mvn package -Dmaven.test.skip=true
	    }
	}
	stage('Test'){
	    steps {
		echo 'Testing..'
	    }
	}
    }
}
