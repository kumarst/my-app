node{
   stage('SCM Checkout'){
     git credentialsId: 'kid1', url: 'https://github.com/kumarst/my-app.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      
      def h = hi
      sh 'echo ${h}'
   }
}
