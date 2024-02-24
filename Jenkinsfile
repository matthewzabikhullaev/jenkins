pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''#!/bin/bash

echo "Hello World"
cat /etc/fstab > newfile.txt'''
      }
    }

  }
}