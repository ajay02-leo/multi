node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
node('built-in')
{
    stage('Continuous Download_master')
        {
    git 'https://github.com/sunildevops77/maven.git'
        }
    stage('Continuous Build_masterbranch')
        {
    sh label: '', script: 'mvn package'
        }

}

