pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        bat label: '', script: 'echo hello world'
        bat label: '', script: '''echo Multiline batch steps work too
        ls -lah'''
      }
    }
  }
}
