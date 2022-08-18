node 
{
    stage('ContinuousDownload') 
    {
       git 'https://github.com/MRaju2022/maven.git'
    }
    stage('ContinuousBuild') 
    {
       sh 'mvn package'
    }

}
