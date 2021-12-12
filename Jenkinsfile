node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sudheerreddyannam/multibranch.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
