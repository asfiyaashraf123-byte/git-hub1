pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                 echo "building started"
                 deleteDir()
                 sh '''
                    git clone https://github.com/asfiyaashraf123-byte/git-hub1.git
                    ls -l
                '''
                }
            }
            stage('deploy'){
                steps{
                    echo "deployment started"
                    sh '''
                        rm -rf /var/www/html/*
                        cp -r git-hub1/* /var/www/html/
                        ls -l /var/www/html/
                    '''
                }
             }
        }
}
    

            
                        
                
            
        
    
