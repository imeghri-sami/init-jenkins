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
                        echo 'mvn -v'
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
