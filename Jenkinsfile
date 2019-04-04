pipeline {
  agent any
  stages {
    stage('parallel_run') {
      parallel {
        stage('parallel_run') {
          steps {
            build 'sample_job_train'
          }
        }
        stage('') {
          steps {
            build 'sample_job_train'
          }
        }
        stage('') {
          steps {
            build 'sample_job_train'
          }
        }
      }
    }
  }
}