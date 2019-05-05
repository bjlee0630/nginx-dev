node ('master') {
  def app

  stage('Clone repository') {
    /* Let's make sure we have the repository cloned to our workspace */
    checkout scm
  }
  stage('Build') {
    app = docker.build("nginx-test")
  }
  stage('Results') {
  }
}
