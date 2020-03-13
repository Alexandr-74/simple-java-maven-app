pipline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh 'mvn -B -DskipTest clean package'
			}
		}	
	}
}
