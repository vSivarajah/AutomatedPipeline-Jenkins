pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                println 'building an artifact' 
            }
        }
        stage('Test'){
            steps {
		println 'testing...'
            }
        }
        stage('Deploy') {
            steps {
		println 'deploying...'
            }
        }
    }
}
