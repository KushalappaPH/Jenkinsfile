pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'This is to build a Pipelinhhhhe'
            }
        }
         stage('test') {
            steps {
                echo 'This is to test a Pipeline'
            }
        }
         stage('deploy') {
            steps {
                echo 'This is to deploy a Pipeline'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'Declarative pipeline', replyTo: 'varunkushalappa11@gmail.com', subject: 'Pipeline', to: 'varunkushalappa11@gmail.com'
        }
    }
    
}
