pipeline {

    agent {
        node {
            label 'master'
        }
    }

    tools { 
        maven 'maven-3269032f' 
    }

    options {
        buildDiscarder logRotator( 
                    daysToKeepStr: '15', 
                    numToKeepStr: '10'
            )
    }

    environment {
        APP_NAME = "limtianzhong"
        APP_ENV  = "DEV"
    }

    stages {
        
        stage('ST1-3269032f') {
            steps {
                echo "ST1-3269032f: Setup Release Environment Completed."
            }
        }
		
        stage('ST2-3269032f') {
            steps {
                echo "ST2-3269032f: Server1 is successfully created"
            }
        }
		
        stage('ST3-3269032f') {
            steps {
                echo "ST3-3269032f: Server1 is healthy – Health check done"
            }
        }
		
        stage('ST4A-3269032f') {
            steps {
                echo "ST4A-3269032f: SQLI Check Completed"
            }
        }
        stage('ST4B-3269032f') {
            steps {
                echo "ST4B-3269032f: XSS Check Completed"
            }
        }
		
        stage('ST5-3269032f') {
            steps {
                echo "ST5-3269032f : Continue the pipeline."
            }
        }
		
        stage('ST6-3269032f') {
            steps {
                echo "ST6-3269032f : Ready for next phase"
            }
        }
    }   
}
