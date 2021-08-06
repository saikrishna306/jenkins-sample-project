pipeline {
    agent {label 'Agent_2_Windows'} 
    stages {
        stage('---clean---') { 
            steps {
                bat "mvn clean"
            }
        }
        stage('--test--') { 
            steps {
                bat "mvn test" 
            }
        }
        stage('--package--') { 
            steps {
                bat "mvn package" 
            }
        }
    }
}
