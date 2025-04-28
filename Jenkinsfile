pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running Unit and Integration Tests with JUnit.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyzing code quality using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running security scan with OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to Staging (AWS EC2).'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging environment.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to Production (AWS EC2).'
            }
        }
        stage('Completed') {
            steps {
                echo 'The Jenkins demo for GitHub is completed.'
            }
        }
    }
}
