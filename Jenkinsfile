pipeline {
  agent any
  stages {
    stage('parallel_run') {
      parallel {
        stage('job1') {
          steps {
            build 'sample_job_train'
          }
        }
        stage('job2') {
          steps {
            build 'sample_job_train'
          }
        }
        stage('job3') {
          steps {
            build 'sample_job_train'
          }
        }
      }
    }
  }
}