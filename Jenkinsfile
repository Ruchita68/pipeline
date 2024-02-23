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
                    sh "javac Demo.java"
                    sh "java Demo"
                    sh "python Main.py"
                }
            }
        }
}
