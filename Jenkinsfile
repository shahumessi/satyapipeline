node{
   stage('Scm checkout'){
     git 'https://github.com/sandeep212/javaclone.git'
   }
   stage('mvn build'){
      sh 'mvn package'
   }
   stage('email configuration'){
     emailext body: 'Email configured sucessfully', 
              replyTo: 'sandeepchowdary212@gmail.com', 
              subject: 'Mail from jenkins', 
              to: 'sandeepchowdary910@gmail.com'

   }
}
