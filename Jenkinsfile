pipeline
{
	agent any
	tools
	{
		maven 'MAVEN_HOME'
	}
	
	stages
	{
		stage('Welcome Stage')
		{
			steps
			{
				echo 'Welcome to Jenkins Pipeline'
			}
		}
		
		stage('Clean Stage')
		{
			steps
			{
				echo 'welcome clean stage'
			}
		}	
        stage('Clean Success Stage')
		{
			steps
			{
				echo 'clean success'
			}
		}			
		stage('Build & Install Stage')
		{
			steps
			{
				echo 'install stage'
			}
		}		
		
		stage('Build Success')
		{
			steps
			{
				echo 'Build successful'
			}
		}
		
	}
}	
