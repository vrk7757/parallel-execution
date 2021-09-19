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
{steps {sh 'echo shell script is running}}
}
}
stage('publish log of both')
{steps{sh'echo upload loggs'}}
}
}
