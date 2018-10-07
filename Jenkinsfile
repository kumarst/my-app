node{
    stage('Git Checkout'){
		git credentialsId: 'kid1', url: 'https://github.com/kumarst/my-app.git'
	}
	
	stage('Maven Build'){
		sh 'mvn clean package'
	}
}
