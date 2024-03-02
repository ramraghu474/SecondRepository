pipeline {
  agent any

  stages {
    stage('Fetch repository') {
      steps {
        git branch: 'main', // Replace with your desired branch or reference
	url: 'https://github.com/ramraghu474/SecondRepository.git' // Replace with your repository URL
	dir : 'project'
      }
    }
    stage('Package code') {
      steps {
        sh '''
          tar -czvf my_code.tar.gz ./project 
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
