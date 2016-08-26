node ('docker') {
  stage 'SCM Checkout'
  checkout scm
}

node ('node1') {
  stage 'Docker image build'
  sh 'docker version'
}

parallel  {
  sh 'docker info'
}

node ('node1') {
  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
