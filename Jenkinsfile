pipeline {
 agent any
  stages {
    sstage ('Build') {
      steps {
        echo "Running Build automation"
        sh './gradlew build --no-daemon'
        archieveArtifacts artifacts: 'dist/trainShedule.zip'
  }
}
