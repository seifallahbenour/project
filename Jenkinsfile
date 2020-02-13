
node {
    stage('Clone') {
        sh label: '', script: 'rm -rf *'
        git 'https://github.com/seifallahbenour/project.git'
    }
    
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
