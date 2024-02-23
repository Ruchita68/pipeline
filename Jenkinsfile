Pipeine
{
    agent any
    stages
    {
        stage("Git")
        {
            steps
            {
                git "https://github.com/Ruchita68/pipeline.git"
            }
        }
            stage("Run")
            {
                steps
                {
                    sh "python Main.py"
                    sh "java Demo.java"
                }
            }
        }
}
