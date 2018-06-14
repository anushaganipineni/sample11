def workspace;
node
{
    stage('checkout')
{
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github1', url: 'https://github.com/anushaganipineni/sample11.git']]])
    workspace=pwd();
}
   stage('static code analysis')
   {
       echo "static code"
   }
   stage('build code')
   {
       echo "build stage"
   }
   stage('test stage')
   {
   echo "test stage"
   }
 }
