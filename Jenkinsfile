pipeline{
	agent any
	stages{
		stage('Stage 1'){
			steps{
				echo pwd()
				echo "yufei zhao"
				sh '''
					java -version
					javac Hello.java
					java Hello
				'''

			}
		}
	}
}

