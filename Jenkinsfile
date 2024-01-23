pipeline {
    agent any

    environment {
        MAVEN_HOME = tool 'Maven' // Make sure 'Maven' is configured in Jenkins
        JAVA_HOME = tool 'JDK' // Make sure 'JDK' is configured in Jenkins
    }

    stages {
        stage('checkout') {
            steps {
            // checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/devops-tarunraj/minepipe.git']])
            }
        }
    stage('Build') {
            steps {
                // Set up the Maven environment
                withMaven(maven: usr/share/maven) {
                    // Run Maven build
                    sh 'mvn clean install'
                    
