pipeline {
    node-1

    stages {
        stage('First-Stage') {
            steps {
                echo 'Hello World'
                sh "mkdir /home/slave-2/slave-2-workspace/demo-22"
               // echo "The build number is  ${BUILD_NUMBER}"
                
            }
        }
       stage('Second-stage') {
            steps {
                echo "The build number is  ${BUILD_NUMBER}"
                echo "The build number is  ${NODE_NAME}"
                
            }
        } 
    }
}
