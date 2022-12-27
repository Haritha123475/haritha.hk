pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'clone is successful from github'
            }
        }
    stage('build') {
            steps {
                echo 'biuld is successful using maven'
            }
        }

     stage('test') {
            steps {
                echo 'test cases executed successfully '
            }
        }
     stage('deploy') {
            steps {
                echo 'deployment is successfully completed'
            }
        }
    }    
}
