pipeline
{
    agent any
    stages
    {
        stage("Download")
        {
            steps
            {
                git 'https://github.com/ShaikAkbar-hub/maven.git'
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
