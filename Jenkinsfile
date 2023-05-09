pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'mvn clean -DskipTests  package'
            }
        }
        
    }
}
