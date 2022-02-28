node {
    stage('Clone') {
        git "https://github.com/psaidani/helloJenkins/go-securi/src/main/java/com/epsi/Fichiers.java"
    }
    stage('Build') {
        sh label: '', script: 'javac Fichier.java'
    }
    stage('Run') {
        sh label: '', script: 'java Fichier'
    }  
}
