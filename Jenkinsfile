node {
   stage('Preparation') {
      git 'https://github.com/KaiHenssen/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}