pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'Building unix ...'
                    }else {
                        echo 'Building on windows...'
                    }
                    
                }
                
            }
        }
        stage('test') {
            steps {
                echo 'Testing ...'
            }
        }
    }
}
