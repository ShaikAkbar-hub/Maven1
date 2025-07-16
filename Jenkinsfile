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
                //echo 'This is fake URL must be modify later'
            }
        }
        stage("build")
        {
            steps
            {
                sh '''mvn package
'''
                //echo 'This is fake command and must be modify later'
            }
        }
    }
}
