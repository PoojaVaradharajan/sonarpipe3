node{
  stage('Build'){
    echo 'Building'
    currentBuild.result = 'SUCCESS'
  }
  stage('Test'){
    echo 'Testing'
  }

  if(currentBuild.result=='SUCCESS'){
    echo 'Looks Good'
  }else{
    echo 'Failed'
  }
}
