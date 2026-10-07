pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                deleteDir()
                sh '''
                    git clone https://github.com/salihalikkal7-salih/sllh.html.git
                    ls -l
                '''
            }
        }
        stage('deploy'){
            steps{
                sh '''
                    cp -r sllh.html/* /var/www/html
                    ls -l /var/www/html
                '''
                    
            }
        }
        
    }
}
