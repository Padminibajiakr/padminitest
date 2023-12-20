pipeline {
    agent any
    stages {
        stage('microegree job only') {
            steps {
                sh 'echo "this is my first job" '
                sh 'echo "this is devops test job" '
                sh 'echo "this is microdegree testing job" '
                
            }
        }
        stage('2nd job') {
            steps {
               sh 'echo " aws and devops test" '               
            }
        }
        stage('hi devops test') {
            steps {
               sh 'echo "padmini test job" '
                
            }
        }
    }
}
