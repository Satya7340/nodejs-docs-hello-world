pipeline
{
agent any
stages{
  
   stage ('scm checkout')
    { steps  { git branch: 'master', url: 'https://github.com/prakashk0301/nodejs-docs-hello-world'    }  }



   stage ('code build')
     { steps { 
       withNPM
        {  sh 'npm install'  } 
    }}

}}
