pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	   
                    stage('Execute shell'){
                        steps {
                            sh ''' #!/usr/bin/
                            
                            apt-get install zip
                            zip -r test-purpose
                            
                            '''
                        }
                           
              	    }  
         	    } 
        }
}
