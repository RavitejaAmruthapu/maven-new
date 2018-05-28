def workspace;
node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/RavitejaAmruthapu/maven-new.git']]])
        workspace =pwd()
    }
    stage('Static Code Analysis')
    {
        echo 'Static Code Analysis'
    }
    stage('Build')
    {
        echo 'Build the code'
    }
    stage('Unit Testing')
    {
        echo 'Unit Testing'
    }
    stage('Delivery')
    {
        echo 'Delivring the code'
    }
}
