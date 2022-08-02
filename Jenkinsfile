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
	      kiuwan applicationName: 'PIPELINE_KIUWAN', connectionProfileUuid: '5PIH-WqhL', failureThreshold: 97.0, label: '',
		      measure: 'NONE', sourcePath: '/', unstableThreshold: 95.0
	  }
    }
	    
      //stage('Deploy') {
      //steps {
        //echo 'Deploying...'
      //}
    //}
  }
}
