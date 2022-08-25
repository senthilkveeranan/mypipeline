node{
  stage('SCM checkout'){
    git 'https://github.com/senthilkveeranan/mypipeline'    
  }
  stage('compile-package'){
  sh 'mvn package'
  }
}
