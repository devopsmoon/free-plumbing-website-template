pipeline{
    agent {
        label 'jenkins-slave1'
    }
    tools{
        java 'jdk'
        maven 'M2_HOME'
    }
    environment{
        name = 'sayeed'
        age = '43'
    }
    stages{
        stage('check'){
            steps{
                echo "welcome to hello worl"
            }
        }
    }
}