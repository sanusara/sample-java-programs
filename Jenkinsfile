pipeline{
tools {
	jdk "JDK 8" 
	maven "Maven 3.6.3"
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
