pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            build 'z_Sanity_dummy1'
          }
        }
        stage('z_RBAC_dummy2') {
          steps {
            build 'z_RBAC_dummy2'
          }
        }
      }
    }
  }
}