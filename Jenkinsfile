node {
  stage('Build') {
    echo 'Building'
  }
  stage('Test') {
    echo 'Testing'
  }

  currentBuild.result = 'SUCCESS'  // Explicitly setting the result

  if (currentBuild.result == 'SUCCESS') {
    echo 'Looks good'
  } else {
    echo 'Failed'
  }
}
