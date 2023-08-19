pipeline{
    agent any
    stages{
        stage('Deploy to remote'){
            steps{
                sh 'scp -r ${WORKSPACE}/* root@16.171.31.236:/var/www/html/yashaswini/'
            }
        }
    }
}
