pipeline {
    agent any
    stages {
        stage('CBuild Stage') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
