pipeline {
    agent any
     stages{
      stage('clean'){
       steps {
         sh 'maven clean'
       }
    }
      stage('compile'){
        steps{
          sh 'maven compile'
        }
      }
      stage("install"){
        steps{
          sh 'maven install'
          sh 'maven package'
        }
      }
    }

}
