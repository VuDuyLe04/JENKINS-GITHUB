pipeline{
    agent any
    stages {
        stage('Clone'){
            steps {
                git 'https://github.com/VuDuyLe04/JENKINS-GITHUB.git'
            }
        }
    }
    post {
        always {
            mail bcc: '', body: 'Yêu tất cả mọi người', cc: '', from: '', replyTo: '', subject: 'Hello World', to: 'vuduyle004@gmail.com'
        }
    }
}