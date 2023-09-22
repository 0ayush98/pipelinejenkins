pipeline {

agent any 

stages {

      stage ('SCM'){
         steps { 
           echo  "the scm job is build"
           git 'https://github.com/HouariZegai/Calculator.git'
           }
	}

      stage ('BUILD'){
	
         steps { 
           echo  "the Build job"
           sh 'mvn compile'         
 }
	}
	
	

      stage ('Deploy'){

        steps { 
           echo  "the deploy job is build"
             sh 'mvn clean package'

           }
      
          } 

}

 
}