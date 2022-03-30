pipeline
{
agent any
  stages
  {
    stage('building the job')
    {
      step('build')
      sh ('mvn clear')
    }
   stage('test the job')
    {
    step('test')
    sh ('mvn test')
    }
   stage('compile the job')
    {
    step('compile')
    sh ('mvn compile')
    }
    stage('deploy the job')
    {
    step('deploy')
    }
  }
}
