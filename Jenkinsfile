pipeline {
    agent any

    tools {
        jdk 'jdk17-new'
        gradle 'gradle2'
    }

    stages{
        stage('echo') {
            steps {
                echo "Hello";
            }
        }

        stage('gradle') {
            steps {
                sh 'gradle bootJar'
            }
        }
    }
}
