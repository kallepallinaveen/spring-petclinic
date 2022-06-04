pipeline {

    agent any

    stages {

        stage("Build"){
            steps {
                sh "./mvnw package"
            }
        }
        stage("Run Unit-Tests"){
            steps {
                sh "./mvnw test"
            }
        }
        stage("Code Analysis"){
            steps {
                echo "Run Code Analysis"
            }
        }
        stage("Upload Artifacts"){
            steps {
                echo "Upload Artifacts"
            }
        }

    }

}