pipeline
{
agent any
  stages
  {
    stage('building the job')
    {
      steps{
        echo "build"
        sh "mvn clean"
    }
    }
   stage('test the job')
    {
      steps{
      echo "test"
      sh "mvn test"
    }
    }
   stage('compile the job')
    {
      steps{
        echo "compile"
        sh "mvn compile"
    }
    }
    stage('deploy the job')
    {
      steps{
        echo "deploy"
    }
  }
}
}
