node('built-in') 
 {
 stage('continuous download') 
   {
    
     git branch: 'main', url: 'https://github.com/Saleemullahpasha/tomcat-application.git'
 
     }   

stage('Continuous build') 

{

sh 'mvn package'

}


}

