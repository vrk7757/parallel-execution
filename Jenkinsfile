pipeline
{
agent any
stages
{
stage('execute parallely')
{
parallel
{
stage('run python script')
{steps {sh 'echo pythone is running'}}
stage('run shell script')
{steps {sh 'shell script is running}}
}
}
stage('publish log of both')
{steps{sh'upload loggs'}}
}
}
