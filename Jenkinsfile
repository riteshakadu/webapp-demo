pipeline{
	agent any;
	stages {
		stage ("Checkout code") {
			steps {
				git 'https://github.com/riteshakadu/webapp-demo.git'
			}
		}
		stage ("build code") {
			steps {
				sh "mvn deploy"
			}
		}
	}
}
