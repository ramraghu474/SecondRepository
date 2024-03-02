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
          tar -czvf my_code.tar.gz ./workspace/my-git-repo --exclude='.git*'
        '''
      }
    }
    stage('Archive artifacts') {
      steps {
        archiveArtifacts artifacts: 'my_code.tar.gz', 
		fingerprint: true
      }
    }
  }
}
