pipeline
{
 
agent any
stages
  {
     stage ('code scm checkout')
    { steps  {  git branch: 'master', url: 'https://github.com/prakashk0301/nodejs-docs-hello-world'  } }
    
     stage ('code build')
    {  steps { sh 'npm install'  } }
  }


}
