
pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
		sh 'echo "Hello World"'
                sh 'npm --version'
		sh '''
			echo "Multiline shell steps works too"
			ls -lah
		'''
            }
        }
    }
}

