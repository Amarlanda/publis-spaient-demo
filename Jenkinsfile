podTemplate(
  label: 'mypod',
  inheritFrom: 'default',
  containers: [
    containerTemplate(
      name: 'maven',
      image: 'maven',
      ttyEnabled: true,
      command: 'cat'
    )
  ]
)
{
  node('mypod') {
    stage ('Extract') {
      checkout scm
    }
    try{
      stage ('Build') {
      container ('maven') {
        mvn package
      } //container
    }
    }//stage
  }//node
}//podTemplate
