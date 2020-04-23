pipeline {
    
    agent any  

    stages {

        stage('Init'){
            steps {
                echo 'Init'
                echo '******************************'
            }
        }

        stage('Yarn Install') {
            steps {
                echo 'Yarn Install'
                echo '******************************'
            }
        }

        stage('Yarn Build') {
            steps {
                echo 'Yarn Build'
                echo '******************************'
            }
        }
        
        stage('Mvn Install') {
            steps {
                echo 'Mvn Install'
                echo '******************************'
            }
        }
        
        stage('Mvn Test') {
            steps {
                echo 'Mvn Test'
                echo '******************************'
            }
        }
        
        stage('Docker Build Image') {
            steps {
                echo 'Docker Build Image'
                echo '******************************'
            }
        }
        
        stage('Docker Push') {
            steps {
                echo 'Docker Push'
                echo '******************************'
            }
        }
        
        stage('Docker Remove Image') {
            steps {
                echo 'Docker Remove Image'
                echo '******************************'
            }
        }

        stage('Deploy') {
            steps{
                echo 'Deploy'
                echo '******************************'
            }
        }
    }
}
