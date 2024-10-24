pipeline{
    agent any

    stages() {
        stage('git clone') {
            step() {
                git 'https://github.com/cagongman/Jenkins_test.git'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('execute sh') {
            steps {
                sh
            }
        }
    }
}