pipeline {
    agent { labal 'prod_agent' }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
	stage('cleanup') {
	    steps {
		echo 'cleaning up.....'
	    }
	}
    }
}
