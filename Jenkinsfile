pipeline {
    agent label slave
    stages{
        stage('HELLO') {
        /* Let's make sure we have the repository cloned to our workspace */
            steps {
                script {
                    bat "echo Hello-World"
                }
            }
        }
        stage('TEST') {
        /* Let's make sure we have the repository cloned to our workspace */
            steps {
                script {
                    bat "echo test"
                    bat "java -version"
                }
            }
        }
    }
}