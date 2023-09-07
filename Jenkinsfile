<<<<<<< HEAD
pipeline{
=======
 pipeline{
>>>>>>> 1fc775dcd8495ccf4e620393627957128f9d8cc5
    agent any 
    tools{
         maven 'M2_HOME'
    }
    stages{
    stage('maven clean'){
        steps{
        sh  'mvn clean'
        }
    }
    stage('maven install'){
        steps{
          sh  'mvn install'
            
        }
    }
    stage('maven package'){
        steps{
         sh   'mvn package'
        }
    }
<<<<<<< HEAD
   stage('upload artifact'){
        steps{
            sh 'curl --upload-file target/bioMedical-0.0.2-SNAPSHOT.jar -u admin:devops -v http://ec2-35-172-150-179.compute-1.amazonaws.com:8081/repository/maven-nexus-repo/'
      }
    }

    }

}
=======
  
}
 }
>>>>>>> 1fc775dcd8495ccf4e620393627957128f9d8cc5
