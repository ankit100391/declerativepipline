pipeline {
      agent any
     parameters {
  string defaultValue: 'master', name: 'branch', trim: true
}
environment {
  branch_name = "${branch}"
}
      stages{
        stage ('BUILD'){
        steps{
            sh ''' 
            sleep 5
            echo "this is build stage"
            '''
            }
         }
          stage ('DEPLOY'){
        steps{
            sh '''
            sleep 5
             echo "this is beploy stage"
            '''
            }
         }
          stage ('TESTING'){
        steps{
            sh '''
            sleep 5
             echo "this is TESTING stage"
            '''
            }
         }
      }
}
