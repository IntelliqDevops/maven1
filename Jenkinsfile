@Library('mylibrary')_

pipeline
{
    agent any
    stages
    {
        stage('Download_Loans')
        {
            steps
            {
                script
                {
                    cicd.gitDownload("maven")
                }
            }
        }
    }
}
