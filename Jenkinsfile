@Library('jenkinslib') _

def tools = new com.devops.tools()

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
               tools.printMessgae("hello000000000000000000")
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
