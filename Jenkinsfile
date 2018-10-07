node{
def mvnHome =  tool name: 'Maven', type: 'maven' 
   stage('SCM Checkout'){
     git credentialsId: 'kid1', url: 'https://github.com/kumarst/my-app.git'
   }
   stage('Compile-Package'){
      // Get maven home path
        
      bat(/"${mvnHome}\bin\mvn" -Dintegration-tests.skip=true clean package/)
   }


}
