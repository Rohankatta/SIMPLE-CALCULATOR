pipeline {
    agent any

    stages {
        stage('build ') {
            steps {
                echo 'this is the build pahse'
            }
        }
        stage('test ') {
            steps {
                echo 'this is the test phase'
            }
        }
        stage('deploy') {
            steps {
                echo 'this is the deploy phase'
            }
        }
        stage('finall') {
            steps {
                echo 'this is the finall phase'
            }
        }
    }
    post{
        always{
            echo 'always post attribute'
        }
    }
}
