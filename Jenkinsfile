pipeline{
    agent java_slave_node
    tools{
        maven 'maven'
    }
    stages{
        stage('build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
