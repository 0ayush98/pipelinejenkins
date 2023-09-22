pipeline {

agent any 

stages {

      stage ('SCM'){
         steps { 
           echo  "the scm job is build"
           git 'https://github.com/jabedhasan21/java-hello-world-with-maven.git'
           }
	}

      stage ('BUILD'){
	
         steps { 
           echo  "the Build job"
           sh 'mvn clean package'
 }
	}
	
	

      stage ('Deploy'){

        steps { 
           echo  "the deploy job is build"
             

           }
      
          } 

}

 
}