pipeline {
    agent any

    stages {
	// stage('Checkout') {
    // /        steps {
    //             checkout([$class: 'GitSCM', branches: [[name: '*/master']], 
    //                       userRemoteConfigs: [[url: 'https://github.com/wildanazman/devops_assignment.git']]])
    //         }
    //     }

        stage('Build and Test') {
            steps {
                script {
                  
                   
                    
                    sh 'docker-compose up -d'  // Run docker-compose up -d

                }
            }
        }
    }
}
