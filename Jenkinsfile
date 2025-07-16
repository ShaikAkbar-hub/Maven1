pipeline
{
    agent any
    stages
    {
        stage("Download")
        {
            steps
            {
                git 'https://github.com/ShaikAkbar-hub/Maven1.git'
            }
        }
        stage("build")
        {
            steps
            {
                sh '''mvn package
'''
            }
        }
    }
}
