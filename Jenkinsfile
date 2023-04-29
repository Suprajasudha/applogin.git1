pipeline {
    agent any //{label "my-agent"}
    stages {
        stage ("git clone") {
            steps {
                git url: 'https://github.com/tejesh555/applogin.git'
            }
        }
        stage ("build") {
            steps { 
                sh "mvn clean install"
            }
        }
        
    }
}

