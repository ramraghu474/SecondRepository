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
  tar -czvf my_code.tar.gz C:/ProgramData/Jenkins/.jenkins/workspace/ashok@script/0fe30d4067bcd1c44381f604e379bf3e54d57dc033245a59ea4630f8e484df28
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
