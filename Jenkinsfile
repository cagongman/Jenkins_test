pipeline{
    agent any

    stages() {
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'deploying...'
            }
        }
        stage('test git webhook') {
            steps {
                echo 'push detected...2'
            }
        }
    }
}