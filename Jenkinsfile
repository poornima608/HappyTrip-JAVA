node{
stage('SCM Checkout'){

git 'https://github.com/poornima608/HappyTrip-JAVA'}
stage('compile-Package'){
def mvnHome = tool name: 'maven', type: 'maven'
bat "${mvnHome}/bin/mvn package"
}
}
