pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is sriniva aleti from devops training'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy stage') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
			stage('Deploy prod') {
                  steps {
                        echo "Deploying in prod Area"
                  }
            }
            
            }
      }
