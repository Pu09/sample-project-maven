pipeline {
    agent any
    tools{
        maven 'maven'
    }
            stages{
                stage('Clean') {
                    steps {
                        bat 'mvn clean'
                    }
                }
            }
            stage('Build') {
                steps {
                    bat'mvn package'
                }

            }
}