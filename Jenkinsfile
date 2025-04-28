
pipeline{

//Agent Any
agent {
	docker{
		image 'node:18.3'
	}
}
stages{

	stage ('build'){
    steps{

		echo 'Maven --Version'
		echo 'build'
	}

	}
	stage ('Test'){
    steps{

		
		echo 'Test'
	}

	}
	stage ('Integration Test'){
    steps{

		echo 'Integration Test'
	}

	}
	
}




}