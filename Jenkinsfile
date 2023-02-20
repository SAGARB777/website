node {
  stage ( 'scm checkout' ){
    'git https://github.com/javahometech/my-app/new/master'
  }
  stage ('compile-package'){
  sh 'mvn package'
    }
}
