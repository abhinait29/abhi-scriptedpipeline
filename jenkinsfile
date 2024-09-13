node {
    
    stage('hello') {
        echo 'Hello World'
    }
    
}

node {
    
     stage('java') {
        
        git branch: 'main', url: 'https://github.com/abhinait29/abhi-javaproject.git'
                bat '''javac App.java
            java App.java'''
    }
    
}

node {
    
    stage('maven') {
       git 'https://github.com/abhinait29/abhi-mvnproject1.git'
                bat 'mvn clean test'
    }
    
}
