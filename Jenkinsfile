pipeline
{
agent any
stages {
stage('checkout')
{
steps{
script {
git credentialsId: 'jenkins-user-github', url: 'https://github.com/Shrungaliv/Test.git'
sh "ls -lart ./*"
sh "git branch -a"
sh "git checkout branchname"
}
}
}
}
}
