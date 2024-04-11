 pipeline {     
    agent {label 'Production'} 
    
    tools {
        jdk 'jdk17'
        maven 'maven3'
    } 

    stages {
        
        
        stage('tests12') {
            steps {
                sh "mvn test"
            }
        }
        

    }
}
