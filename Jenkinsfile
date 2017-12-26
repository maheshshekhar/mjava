pipeline {
  agent any

  stages {
    stage('Say Hello') {
      agent any

      steps {
        sayHello 'Awesome Student!'
      }
    }
    }
    stage('build') {
      steps {
        sh 'ant -f build.xml -v'
      }
    }
}
