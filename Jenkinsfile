pipeline {
    agent any
    tools{
        maven 'maven'
    }
            stages {
                stage('Clean') {
                    steps{
                      bat'mvn clean'
                    }
                }
                stage('Build') {
                    steps{
                        bat 'mvn web3j:generate-sources'
                        bat'mvn package'
                    }
                }

            }
            }
