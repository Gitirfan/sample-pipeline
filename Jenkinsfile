def workspace 
node()
{
   stage ('checkout')
   {
      checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '0c556872-4c4e-4055-8f42-28967bf8cdae', url: 'https://github.com/Gitirfan/sample-pipeline.git']]])
      workspace =pwd()
   }
   
   stage ('unittesting')
   {
      echo "unit testing"
   }
}

   
   
