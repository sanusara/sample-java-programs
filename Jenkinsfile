pipeline{
tools {
	jdk "jdk8" 
	 maven "mvn3.3.8"
}
             
   agent any
        stages{
            stage('build'){
                steps{
                    sh "mvn clean install"
                }
            }
	stage('test'){
                steps{
                    sh "mvn test package"
                }
            }
        }
    }
