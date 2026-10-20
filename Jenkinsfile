pipeline {
    agent any

    stages {
        
        stage('build') {
            steps {
                deleteDir()
                sh '''
                    git clone https://github.com/salihalikkal7-salih/sllh.html.git
                    '''
            }
        }
        stage('deploy') {
            steps {
                sh '''
                    cp -r sllh.html/* /var/www/html/
                '''
                
                    
                
            }
        }
    }
}
