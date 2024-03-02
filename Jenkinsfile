node('built-in') 
{
    stage('Continuous Download_Cards') 
	{
    git 'git@github.com:anuyadav2602/mycode.git'
	}
    stage('Continuous Build_cards') 
	{
    sh label: '', script: 'mvn package'
	}
}
