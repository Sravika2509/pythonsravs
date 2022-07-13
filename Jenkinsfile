pipeline
{
  agent any
  stages
  {
    stage('Build')
    {
      steps
      {
        sh 'echo "Hi"'
        
      }
      stage('BuildMore')
    {
      steps
      {
             sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
      }
    }
    }
  }  
}
