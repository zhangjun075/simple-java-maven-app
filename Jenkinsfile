pipeline {
     agent any
#    agent {
#        docker {
#            image 'maven:3-alpine' 
#            args '-v /Users/junzhang/.m2:/root/.m2' 
#        }
#    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
