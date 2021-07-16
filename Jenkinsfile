pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        echo 'hello test area'
	echo "congrats good work"
      }
    }

    stage('uat') {
      steps {
        echo 'hello uat area'
      }
    }

  }
  environment {
    building = 'hello environment area'
  }
}
