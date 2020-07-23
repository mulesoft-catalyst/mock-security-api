pipeline {
	agent any
	stages{
		stage("Build"){
		  steps{
			sh "mvn -version"
			sh "man clean package"
		  }
		}
		
	}
	post{
		always{
			cleanWs()
		}
	}
}