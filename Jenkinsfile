pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby hello_world.rb > hello_world'
            }
        }
    }
}
