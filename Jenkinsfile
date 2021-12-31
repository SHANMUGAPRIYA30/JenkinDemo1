pipeline {
    agent any

    stages {
        stage('Acknowledge') {
            steps {
                echo 'Automatic build has taken place'
            }
        }
        
         stage('Clone') {
            steps {
                echo 'Cloing the github repository'
                bat 'git clone https://github.com/SHANMUGAPRIYA30/JenkinDemo1.git'
                echo 'Pulled the code'
        }
    }
}
}
