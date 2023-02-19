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
		stage('Deploy'){
			steps{
				echo 'Pipeline deployed succesfully! by Swapnil'
				}
			}


}

}
