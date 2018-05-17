pipeline {
    agent any

    stages {
        stage('Unit test') {
              steps {
                // Compile and run the unit tests for the app and its dependencies
                //
                 echo 'Testing..'
                bat './gradlew testDebugUnitTest'
                 echo 'Tested..'
              }
            }
    }
}