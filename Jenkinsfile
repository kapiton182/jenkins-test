pipeline {
      agent any
      stages {
        stage('No-op') {
            steps {
                sh 'ls'
            }
        }
    }
   post {
    always {
        mail to: 'kapiton182@gmail.com',
             subject: "Failed Pipeline:FUCKED}",
             body: "Something is wrong with YOU"
    }
}
}
