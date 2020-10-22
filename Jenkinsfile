pipeline {
   agent any

   triggers {
    cron '''TZ=Etc/UTC
H/5 * * * *'''
  }
   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
