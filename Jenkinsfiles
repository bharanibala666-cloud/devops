pipeline
{
    agent any
        stages
        {
            stage('clone')
            {
                steps
                {
                    git branch:'devops3',url:'https://github.com/bharanibala666-cloud/csea.git'
                }
            }
            stage('build')
            {
                steps
                {
                    sh 'javac hello.java'
                }
            }
            stage ('run')
            {
                steps
                {
                sh 'java hello'
                }
            }
        }
}
