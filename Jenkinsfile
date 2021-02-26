pipeline {
    node-1

    stages {
        stage('First-Stage') {
            steps {
                checkout scm
                echo 'Hello World'
                sh "mkdir /home/slave-2/slave-2-workspace/demo-22"
               // echo "The build number is  ${BUILD_NUMBER}"
                
            }
        }
       
    }
}
