pipeline {

    agent any

    stages {

        stage("Build"){
            steps {
                sh "./mvnw clean package"
            }
        }
        stage("Run Unit-Tests"){
            steps {
                sh "./mvnw test"
            }
        }
        stage("codeAnalysis"){
            
        }
        stage("Upload Artifacts"){
            steps {
                echo "Upload Artifacts"
            }
        }

    }

}