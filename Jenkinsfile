pipeline {
    agent { docker { image 'ruby' } }

    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
                sh 'ruby hello_world.rb'
            }
        }
    }
}
