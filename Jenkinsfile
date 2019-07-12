pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               
                    sh 'mvn clean install'
                
            }
        }

    /*    stage ('Testing Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
                }
            }
        }
*/

       
    }
}
