pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                withMaven(maven: 'maven_3_6_3') {
                    sh 'mvn clean install -DskipTests'
                }
            }
        }

        stage('build') {
            steps {
                withMaven(maven: 'maven_3_6_3') {
                    sh 'mvn clean install -DskipTests'
                }
            }
        }
    }
}