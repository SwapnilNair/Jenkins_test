pipeline{
agent any
	stages{
		stage('Build'){
			steps{
				sh 'make'
				}
			      }
		stage('Run'){
			steps{
				sh './hello_exec'
				}
		}


}

}
