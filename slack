node{
   stage('Scm checkout'){
     git 'https://github.com/sandeep212/javaclone.git'
   }
   stage('mvn build'){
      sh 'mvn package'
   }
   stage('email Notification'){
     mail bcc: '', 
        body: '''build the job successfully
        from sandeep''', cc: '', from: '', replyTo: '', 
        subject: 'jenkins job', 
        to: 'sandeepchowdary910@gmail.com'
   }
}
