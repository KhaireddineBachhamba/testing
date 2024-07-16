pipeline{
    agent any

    environment{
        PATH = "/opt/maven3/bin:$PATH"
    
    }
    stages{
        stage("Git Checkout"){
            steps{
                echo "Hello world"
            }
        }

        stage("Maven Build"){
            steps{
                sh "mvn clean package"          
            }
        
        }
    }
}
