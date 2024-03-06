pipeline {
    agent any
    environment{
       test = "xy" 
    }
    stages {
        stage('Hello') {
            steps {
                cleanWs()
                echo 'Hello World'
                sh 'mkdir folder'
                sh 'ls -lart'
                sh 'pwd'
                print BUILD_URL
                sh "echo tool name is tool"
            }
        }
    }
}
