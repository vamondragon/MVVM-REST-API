pipeline {
  agent any
  stages {
    stage('') {
      steps {
        build(job: './gradlew compileDebugSources', quietPeriod: 1)
      }
    }

  }
  environment {
    Compile = 'compile'
  }
}