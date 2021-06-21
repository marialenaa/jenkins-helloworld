node {
    stage('Clone') {
        git credentialsId: 'marialenaa', url: 'https://github.com/marialenaa/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
