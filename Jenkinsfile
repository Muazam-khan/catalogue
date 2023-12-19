 @Library('jenkins-shared-library') _
 pipeline {
    agent any
        //label "ws"
    //}
    stages{
        stage('Lint Checks'){
          steps {
            script {
                nodejs.lintChecks()
            }
           
        }
          
    }
        stage('Static Code Analysis'){
          steps {
            sh "echo ***** Starting Static Code Analysis *****"
       }
          
    }

  }
}