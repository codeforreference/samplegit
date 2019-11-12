pipeline {
    stages {
        stage('Build') {
         
            steps {
                when {
                branch 'test'
            }
                git 'https://github.com/codeforreference/samplegit.git'
            }
        }
    }
}
