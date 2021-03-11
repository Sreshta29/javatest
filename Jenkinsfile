pipeline
{
   agent any
 
    
   
    stages
    {
    stage('Build')
    {
       steps
        {
            sh 'mvn clean install'
        }
    }
    stage('Deploy')
    {
        steps
        {
            sh 'sudo cp target/*.war /var/lib/tomcat8/webapps'
       
        }
    }
    }
}
