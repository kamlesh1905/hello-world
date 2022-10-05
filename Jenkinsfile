
node{
   stages('SCM checkout')
   {
       git  'https://github.com/kamlesh1905/hello-world'
    }
     stages('Compile-Package')
   {
      def mvnHome = tool name: 'maven', type: 'maven'
      sh "${mvnHome}/opt/maven clean install"
    }
    
}
