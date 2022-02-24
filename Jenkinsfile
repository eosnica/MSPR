node {
    stage('Clone') {
        git "https://github.com/psaidani/helloJenkins"
        cp Rp /var/www/html'
    }
    stage('Build') {
        sh label: '', script: 'javac hello.java'
    }
    stage('Run') {
        sh label: '', script: 'java hello'
    }
    stage('Deploy') {
        sh 'cp MSPR/tree/main/go-securi/src/main/java/com/epsi /var/www/html'
    }
}
