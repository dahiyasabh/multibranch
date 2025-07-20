node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/dahiyasabh/maven.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
