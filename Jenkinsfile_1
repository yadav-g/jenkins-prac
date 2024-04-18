pipeline{
  agent any
  parameters{
    choice(name:'VERSION',choices:['1.1.0','1.2.3'],description:'The version of application used')
  }
    stages{
      stage("build"){
        steps{
          echo "first jenkins pipeline"
          echo "The version used is ${params.VERSION}"
        }
      }
    }
  }
