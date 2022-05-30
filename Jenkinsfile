pipeline{
    agent any
    stages{
        stage ("Build"){
            steps{
                script{
                    echo "Building new application..."
                }  
            }
        }
        stage("Test"){
            steps{
                script{
                    echo "Testing new application..."
                }
            }
        }
	stage("Deploy"){
            steps{
                script{
                    echo "Deploying the application in to the prod Environment..."
		}
	    }
	}	

    }    
}
