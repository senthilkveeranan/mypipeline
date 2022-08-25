node{
  stage('SCM checkout'){
    git 'https://github.com/senthilkveeranan/mypipeline'    
  }
  stage('Compile-Package'){
  sh 'mvn package'
  }
}
