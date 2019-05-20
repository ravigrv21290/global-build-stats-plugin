pipeline {
    agent any
    stages {
        stage('global_build_statistics') {
            steps {
                echo "Build!"
                sh 'java -version'
              buildPlugin()
            }
        }
    }
}

