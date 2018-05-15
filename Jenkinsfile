pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            svn 'http://127.0.0.1/svn/adaaad'
            echo 'awdafe'
          }
        }
        stage('') {
          steps {
            timestamps() {
              sh 'echo $JAVA_HOME'
            }

          }
        }
      }
    }
    stage('test') {
      steps {
        sleep 3
        timestamps() {
          sleep 1
        }

      }
    }
  }
}