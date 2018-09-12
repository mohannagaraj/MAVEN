node {
     stage('checkout code from scm git '){
       git 'https://github.com/mohannagaraj/MAVEN/'
       }
     stage('compile & build the package'){
       def mvnhome =  tool name: 'maven3', type: 'maven'
       sh "${mvnhome}/bin/mvn package"
       }
       
       }
