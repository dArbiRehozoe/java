node {
    stage('Clone') {
        git 'https://github.com/dArbiRehozoe/java.git'
        sh '''javac Main.java
            java Main'''
    }
    stage('Build') {
       sh 'javac Main.java'
        
    }
    stage('Run') {
       sh 'java Main'
    }
}
