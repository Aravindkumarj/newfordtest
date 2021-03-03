@Library('piper-lib-os') _

node() {
  
  stage('Deploy') {
    gctsDeploy(
        script: this,
        host: 'phlhdr07.phl.sap.corp:8001',
        client: '200',
        abapCredentialsId: 'ABAPUserPasswordCredentialsId',
        repository: 'fordtest2',
      )
  }
}
