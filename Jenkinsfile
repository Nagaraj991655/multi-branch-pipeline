pipeline {
	agent any

	stages {
	  stage('build') {
	    steps {
	        echo 'Building Application'
                }
          }
          stage('test') {
            steps {
                echo 'Testing the application'
                }
          }
          stage('deploy') {
            steps {
                echo "Current branch: ${env.BRANCH_NAME}"
                }
          }
       }
}
        
