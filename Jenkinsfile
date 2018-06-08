pipeline {
    agent any

environment {
             ANDROID_HOME = 'C:/Users/vardan.mkrtchyan/AppData/Local/Android/Sdk'
         }
    stages {
        stage('Unit test') {
              steps {
                // Compile and run the unit tests for the app and its dependencies
                 echo 'Testing..'
                 echo env.BRANCH_NAME
                sh './gradlew testDebugUnitTest'
                 echo 'Tested..'
              }
            }
    }
}