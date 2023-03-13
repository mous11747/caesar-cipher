pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               sh './gradlew build'
           }
       }
       stage('Test') {
           steps {
               sh './gradlew test'
           }
       }
       stage('Release') {
           steps {
               sh './gradlew jar -PmainClass=com.mous.CaesarCipher'
           }
       }
       stage('Deploy') {
           steps {
               // Add deployment steps here
               echo 'Deploying....'
           }
       }
   }
}
