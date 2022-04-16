pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'Building unix ...'
                    }else {
                        echo 'Getting maven verison ...'
                        sh 'mvn -v'
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
