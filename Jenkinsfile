pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/jdossa68/node-hello.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
  }
