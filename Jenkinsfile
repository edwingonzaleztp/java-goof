pipeline {
  agent { label 'generic' }

  stages {
    //stage('Build') {
      //steps {
        //echo 'Building...'
      //}
    //}
  	  
    stage('Test_Kiuwan') {
      steps {
        echo 'Testing Kiuwan...'
	      kiuwan applicationName: 'PIPELINE_SEGURIDAD', connectionProfileUuid: '5PIH-WqhL', 
		      failureThreshold: 98.0, label: '', sourcePath: '/', unstableThreshold: 99.0
	  }
    }
	    
      //stage('Deploy') {
      //steps {
        //echo 'Deploying...'
      //}
    //}
  }
}
