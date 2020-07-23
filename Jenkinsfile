pipeline {
	agent any
	stages{
		stage("Build"){
			sh "mvn -version"
			sh "man clean package"
		}
		
	}
	post{
		always{
			clean
		}
	}
}