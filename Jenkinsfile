pipeline {
   agent any

   triggers { cron('H 4/* 0 0 1-5') }

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
