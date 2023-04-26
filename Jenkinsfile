node{
    
    stage('checkout') {
 git branch: 'master',  url: 'https://github.com/krkumar14/simple-java-maven-app.git'   
 }


stage('build') {
    
        println "build is running"
        
        sh " /opt/maven/bin/mvn clean deploy -DskipTests "
    
}
}
