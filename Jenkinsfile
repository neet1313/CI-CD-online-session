pipeline {
  agent any
  stages {
    stage('Built') {
      steps {
        script {
          checkout scm



          def

          customImage = docker.build("${registry}:${env.BUILD_ID}")
        }

      }
    }

  }
  environment {
    registry = 'neet13 / ci_cd_pipeline_session'
  }
}