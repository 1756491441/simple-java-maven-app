pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '#!/bin/bash -il'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}