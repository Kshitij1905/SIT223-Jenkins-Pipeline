pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven'
                echo 'Tool: Maven - compiles and packages the application'
            }
        }
        
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit'
                echo 'Running integration tests with Selenium'
                echo 'Tools: JUnit, Selenium'
            }
        }
        
        stage('Code Analysis') {
            steps {
                echo 'Analyzing code quality with SonarQube'
                echo 'Tool: SonarQube - checks code against industry standards'
            }
        }
        
        stage('Security Scan') {
            steps {
                echo 'Performing security scan with OWASP Dependency-Check'
                echo 'Tool: OWASP Dependency-Check - identifies vulnerabilities'
            }
        }
        
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
                echo 'Tool: AWS CLI / Jenkins AWS plugin'
            }
        }
        
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging environment'
                echo 'Tool: Postman / Newman for API testing'
            }
        }
        
        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to AWS EC2 production server'
                echo 'Tool: AWS CLI / Ansible for deployment automation'
            }
        }
    }
}
