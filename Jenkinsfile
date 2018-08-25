
pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
		sh 'echo "Hello World in branch2 ------======="'
                sh 'npm --version'
		sh '''
			echo "======branch2======== Multiline shell steps works too"
			ls -lah
		'''
            }
        }
    }
}

