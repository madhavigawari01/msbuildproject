pipeline {
	
	agent any 
	
		stages {
		
			stage ('Compile Stage')	
			{
			steps {
				echo "Compiling...."	
				sh 'date'
				}
			}

			stage ('Testing Stage') 
			{
                	steps {
				echo "Testing ....."
                                sh 'whoami'
                                }
                 	}

			stage ('Deployment Stage') 
			{
                	steps {
				echo "Deploying ....."
                                sh 'lastlog'
                               }
                 	}
		}

	}

