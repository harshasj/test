pipeline {
  agent {
		label 'project_java'
     }
  stages{
       
	   stage('Build') {
			steps{
				echo 'Building in progress .........'
				sh 'sleep 30'
			}
       } 
	   stage('Test ') {
	   parallel{
			steps{
				echo 'Testing in progress .........'
				sh 'sleep 30'
			}
			}
       }
	   stage('Deploy') {
			steps{
				echo 'Deployment  in progress .........'
				sh 'sleep 30'
			}
       }
	   
     }
}
