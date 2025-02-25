pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'http:/github.com/ram9014673/demo2_rep.git'
}
}
stage('build)
{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh'java hello'
}
}
}
}
