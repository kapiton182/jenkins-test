pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
   post {
    failure {
        mail to: 'kapiton182@gmail.com',
             subject: "Failed Pipeline:FUCKED}",
             body: "Something is wrong with YOU"
    }
}
}
