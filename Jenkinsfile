pipeline {
    agent any
    triggers {
        POLLSCM('H/2 * * * *')
    }

    stages {
        stage("Hello") {
            steps {
                echo "Hello All Welcome to Devops World"
            }
        }
        stages {
            stage("changing poll") {
                steps {
                    echo "new changes added"
                }
            }
        }
    }
}
