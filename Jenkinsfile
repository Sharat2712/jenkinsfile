pipeline
{
    agent any
    stages
    {
        stage ('Compile')
        {
            agent any
            steps
            {
                sh 'mvn compile'
            }
        }
        stage ('Test Step')
        {
            agent any
            steps
            {
                sh 'mvn test'
            }

        }
        stage ('Package Project')
        {
            agent any
            steps
            {
                sh 'mvn package'
		}
        }
    }
}

