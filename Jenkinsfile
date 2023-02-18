node{
    git branch:'main',url:'https://github.com/mesbahmohamed/Simple-JavaApp.git'
    stage('build'){
        try{
            sh('echo "Hello Mohamed This is Build Stage"')
        }
        catch(Exception e){
            sh('echo "Exception Found " ')
            throw e 
        }

        
    }
    stage('test')
    {
        if(env.BRANCH_NAME=="feat"){
            sh('echo "Test Stage"')
        }
        else{
            sh('echo "Test"')
        }
        
        
    }
}