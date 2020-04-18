node {

   stage('SCM') {
      // git clone
	  git 'https://github.com/gyana210/gol.git'
   }
   
   stage ('build the packages') {
      // mvn package
	  sh 'mvn package'
   }

   
   
   stage ('archival') {
     // archiving artifacts
	 archive 'target/*.jar'
   }

}