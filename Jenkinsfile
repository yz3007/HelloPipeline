pipeline{
	agent any
	stages{
		stage('Stage 1'){
			steps{
				cd ~/test-pipeline/
				javac Hello.java
				java Hello
			}
		}
	}
}

