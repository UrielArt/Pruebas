pipeline {
   agent any
   stages {
       stage('RAMA') {
           steps {
               git branch: 'main', url: 'https://github.com/UrielArt/Pruebas.git'
               
           }
       }
       stage('Hola') {
           steps {
               print "hola mundo"
           }
       }
   }
}