
pipeline { 
    agent any 
    stages {
        stage('clean') { 
            steps { 
               sh "mvn clean"
            }
        }
        stage('Test'){
            steps {
                sh 'make test'
             
            }
        }
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
