def workspace;

node
{
    stage('checkout'){
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/benchmark-bits/jenkintest.git']]])
    
        workspace = pwd()
    }
    
    stage('build'){
        
        echo "build done"
    }
    
    stage('deploy'){
        
        echo "deploy done"
    }
}
