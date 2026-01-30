pipeline
{
    agent any
        stages
        {
            stage('clone')
            {
                steps
                {
                    git branch:'devopscsea',url:'https://github.com/bharanibala666-cloud/devops.git'
                }
            }
            stage('build')
            {
                steps
                {
                    sh 'javac Hello.java'
                }
            }
            stage('run')
            {
                steps
                {
                    sh 'java Hello'
                }
            }
        }
}
