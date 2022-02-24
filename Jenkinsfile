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
    
    //sh 'cp chemin /
}
