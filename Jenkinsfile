pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Anshul from LevelUp360'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Test Environment"
                  }
            }
            stage('Deploy Staging') {
                  steps {
                        echo "Deploying in Staging Environment"
                  }
            }
             stage('Deploy Prod') {
                  steps {
                        echo "Deploying in Production Environment"
                  }
            }
      }
}
