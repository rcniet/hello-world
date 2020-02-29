node {
   // This is to demo github action	
   // def sonarUrl = 'sonar.host.url=http://172.31.30.136:9000'
    def mvn = tool (name: 'maven3', type: 'maven') + '/opt/maven/bin'
   stage('SCM Checkout'){
    // Clone repo
	git branch: 'master', 
	url: 'https://github.com/rcniet/hello-world.git'
	   
	    stage ('build maven'){
		   sh label: '', script: 'clean install package'
	   }
	

   }
	
}

	
   
