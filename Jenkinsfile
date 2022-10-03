pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */


   agent any
       stages {
           stage('assemble') {
               steps {
                   //echo 'Hello Assembler'
                   /gradlew assemble
               }
           }
           stage('test') {
               steps {
                   //echo 'Hello Tester'
                   /gradlew test
               }
           }
       }
}
