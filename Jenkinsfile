pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build'
                echo 'Tool used: Maven'
                echo 'This stage compiles and packages the application code.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests'
                echo 'Tools used: JUnit and Selenium'
                echo 'This stage runs unit tests and checks that different parts of the application work together.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis'
                echo 'Tool used: SonarQube'
                echo 'This stage checks code quality, bugs, and security hotspots.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan'
                echo 'Tool used: OWASP Dependency-Check'
                echo 'This stage scans the project for known security vulnerabilities.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging'
                echo 'Tool used: AWS EC2'
                echo 'This stage deploys the application to a staging server for testing.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging'
                echo 'Tool used: Postman/Newman'
                echo 'This stage tests the application in a production-like environment.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production'
                echo 'Tool used: AWS EC2'
                echo 'This stage deploys the final tested application to the production server.'
            }
        }
    }
}
