
node{
   stages('SCM checkout')
   {
       git  'https://github.com/kamlesh1905/hello-world'
    }
     stages('Compile-Package')
   {
       sh 'mvn clean install'
    }
    
}
