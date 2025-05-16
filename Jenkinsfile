pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "Stage 1: Build"
                echo "Task: Compile and package the code"
                echo "Tool: Maven - A build automation tool that can be used to compile Java code and package it into JAR files"
            }
        }
        
        stage('Unit and Integration Tests') {
            steps {
                echo "Stage 2: Unit and Integration Tests"
                echo "Task: Run automated tests to ensure code functionality and component integration"
                echo "Tools: JUnit for unit testing and Selenium for integration testing"
            }
        }
        
        stage('Code Analysis') {
            steps {
                echo "Stage 3: Code Analysis"
                echo "Task: Analyze code for quality, style, and potential issues"
                echo "Tool: ESLint for JavaScript code analysis to ensure it meets industry standards"
            }
        }
        
        stage('Security Scan') {
            steps {
                echo "Stage 4: Security Scan"
                echo "Task: Scan code for security vulnerabilities"
                echo "Tool: OWASP Dependency-Check to identify vulnerable dependencies"
            }
        }
        
        stage('Deploy to Staging') {
            steps {
                echo "Stage 5: Deploy to Staging"
                echo "Task: Deploy application to staging environment"
                echo "Tool: AWS CLI to deploy to an EC2 staging instance"
            }
        }
        
        stage('Integration Tests on Staging') {
            steps {
                echo "Stage 6: Integration Tests on Staging"
                echo "Task: Run integration tests in staging environment"
                echo "Tool: Postman for API testing in the staging environment"
            }
        }
        
        stage('Deploy to Production') {
            steps {
                echo "Stage 7: Deploy to Production"
                echo "Task: Deploy application to production environment"
                echo "Tool: AWS CLI to deploy to an EC2 production instance"
            }
        }
    }
}