

node{

//Build Stage and SonarQube 
	stage ('git'){checkout scm}
	stage ('Build') {
		
		sh ''' chmod 777 ./sample.sh'''
	sh '''./sample.sh'''
	
	}



	stage ('Test Build') {
		sh '''ls -la file.sh'''
		sh '''chmod 774 file.sh'''
		sh '''./file.sh'''
	}
	stage ('deploy') {
		sh '''ls -la testing.sh'''
		sh '''chmod 774 testing.sh'''
		sh '''./testing.sh'''
	}
}

