node('built-in') 
{
    stage('ContinuousDownload_master') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('ContinuousBuild_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
