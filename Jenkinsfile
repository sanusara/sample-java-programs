pipeline{
tools {
	jdk "JDK" 
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
