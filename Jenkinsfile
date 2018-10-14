pipeline {
          agent any
    stages {
        stage('printing hostname') {
            steps {
                sh 'hostname'
                sh 'hostname -i'
	}
	   }
                stage('build') {
                steps {
                    withMaven(maven: 'maven') {
                        sh 'mvn clean install'
		
		}                        
		}
}
