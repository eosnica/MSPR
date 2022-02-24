node {
    stage('Clone') {
        git "https://github.com/psaidani/helloJenkins"
    }
    stage('Build') {
        sh label: '', script: 'javac hello.java'
    }
    stage('Run') {
        sh label: '', script: 'java hello'
    }
    stage('Deploy') {
        steps { 
            dir('MSPR'){
        sh 'cp MSPR/tree/main/go-securi/src/main/java/com/epsi /var/www/html'
        }
    }
}
}
