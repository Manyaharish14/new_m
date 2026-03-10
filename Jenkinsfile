pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git branch: 'main',
          url : 'https://github.com/Manyaharish14/new_m.git'
      }
    }
    stage('Run Script'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
