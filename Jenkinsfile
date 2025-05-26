pipeline{
  agent any

  stages{
    stage('Clone Repo'){
      steps{
        git branch: 'main', url:'https://github.com/velvignesh6404/p2git.git'
      }
    }

    stage('Building'){
      steps{
        echo 'Building'
      }
    }

    stage('Testing'){
      steps{
        echo 'Testing'
      }
    }

    stage('Deploying'){
      steps{
        echo 'Deploying'
      }
    }
  }
}
