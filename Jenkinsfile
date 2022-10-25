
node{
   stage('SCM checkout')
   {
       git  'https://github.com/kamlesh1905/hello-world'
    }
     stage('Compile-Package')
   {
      def mvnHome = tool name: 'maven', type: 'maven'
      sh "${mvnHome} clean install"
    }
    
}
