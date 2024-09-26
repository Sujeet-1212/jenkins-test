pipeline
{
  agent any
  stages
  {
    stage('print message')
    {steps{ sh 'echo Hello' }}
    
     stage('scm checkout')
    {steps{git branch: 'main', url: 'https://github.com/Sujeet-1212/jenkins-test.git' }}

    
  }
}
