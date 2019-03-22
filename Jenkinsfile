pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        svn 'http://svn.it.egltours.com/svn/repos/nfit/portal_one/trunk/portal-one-parent'
        build 'pipelinetest'
      }
    }
  }
}