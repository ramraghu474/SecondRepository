pipeline {
  agent any

  stages {
    stage('Fetch repository') {
      steps {
        git branch: 'main', // Replace with your desired branch or reference
	url: 'https://github.com/ramraghu474/SecondRepository.git' // Replace with your repository URL
	
      }
    }
    stage('Package code') {
      steps {
        sh '''
  		python --version
	'''

      }
    }
    stage('Archive artifacts') {
      steps {
        echo 'Raghuram'
      }
    }
  }
}
