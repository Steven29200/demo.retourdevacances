pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
       jdk "jdk17-0-5" 
    }

    stages {
        stage('Build') {
            steps {
                 git 'https://github.com/Steven29200/demo.retourdevacances.git'
                dir("demo.retourdevacances"){
                 sh "chmod +x ./gradlew"
                sh "./gradlew build" 
                }
                

                
            }

            
            }
        }
    }
