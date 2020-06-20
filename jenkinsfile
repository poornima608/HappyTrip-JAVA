node{
stage('SCM Checkout'){

git 'https://github.com/poornima608/HappyTrip-JAVA'}
stage('compile-Package'){
def mvnHome = tool name: 'maven', type: 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
