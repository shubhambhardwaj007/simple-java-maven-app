pipeline{
  agent none
  stages{
    stage("Build"){
      agent {
        label "myslavemaven"
      }
      steps{
        echo "my first step in master branch"
      }
    }
    
  }
}
