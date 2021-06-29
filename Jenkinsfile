pipeline {
        agent any
    
        stages {
            stage('Build') {
               steps {
                  script {
               try
               {
                   git 'https://github.com/ziyoteam1/project.git'
                   sh "python3 fizzbuzz.py"
               }
               catch(err)
               {
                   echo err.nessage
               }
              }
             }
            }
        }
    }
