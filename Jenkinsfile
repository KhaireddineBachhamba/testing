pipeline{
    agent any

    environment{
        PATH = "/usr/share/maven/bin:$PATH"
    
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
