pipeline{
	agent any
	stages{
	stage('SCM - Checkout'){
			steps{
				git url: 'https://github.com/rcniet/hello-world'
	stage('Maven Build'){
					steps{
					sh "mvn clean package"
					
					}
			}
		}
	
					
 }

}
