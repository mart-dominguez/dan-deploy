#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
      stage('deploy') {
        steps {
          bat "docker-compose -f docker-compose-app.yml up --build -d"
        }
      }
    }
}