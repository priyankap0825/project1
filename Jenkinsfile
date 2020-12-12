pipeline {
       agent any
       stages {
              stage('build') {
                     steps {
                            echo 'hello'
                            sh 'java -version'
                            sh 'mvn clean'
                     }
              }
              stage('unit test') {
                     steps {
                            echo 'hello1'
                     }
              }
              stage('integration test') {
                     steps {
                            echo 'hello2'
                     }
              }
              stage('feature test') {
                     steps {
                            echo 'hello3'
                     }
              }
              stage('devlopment deploy') {
                     steps {
                            echo 'hello4'
                     }
              }
              stage('qa deploy') {
                     steps {
                            echo 'hello5'
                     }
              }
              stage('performance deploy') {
                     steps {
                            echo 'hello6'
                     }
              }
              stage('production deploy') {
                     steps {
                            echo 'hello7'
                     }
              }
       }
}
