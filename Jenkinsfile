pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    git credentialsId: '937d0a4a-369e-4b50-bb05-b0ab27bccd37', url: 'https://github.com/Nagandhra/onlinebookstore.git' 
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
