node{
   stage('Scm checkout'){
     git 'https://github.com/sandeep212/javaclone.git'
   }
   stage('mvn build'){
      sh 'mvn package'
   }
}
