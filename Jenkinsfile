pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git credentialsId: 'keyGithub', url: 'https://github.com/pesquerra/EjercicoSistemaNoticias.git'
            }
        }
    }
}
