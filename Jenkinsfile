node('built-in') 
{
    stage('ContinuousDownload_loans') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('ContinuousBuild_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
