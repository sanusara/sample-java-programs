pipeline{
tools {
	jdk "JDK 8" 
	maven "Maven"
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