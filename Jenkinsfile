pipeline {
    agent any

    stages {
        stage('git clone & build') {
            steps {
                parallel(
                    a: {
                        echo 'git clone'
                        echo 'git Jenkins'
                    },
                    b: {
                        echo 'build'
                    }
                    )
                }
        }
       
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}

