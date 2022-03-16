node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Gopichand2949/rep3.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
