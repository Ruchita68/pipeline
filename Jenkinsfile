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
                    sh "java Demo.java"
                    sh "python Main.py"
                }
            }
        }
}
