pipeline{
    agent any 

    stages{
        
        stage("test"){

            steps{
                git branch: 'main', url: 'https://github.com/shivam779823/sample.git'
            }
        }

        stage("build"){

            steps{
                sh 'docker build -t hellow .'
                
            }
        }

        
        }
    }


