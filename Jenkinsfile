pipeline {
    agent any

    tools {
        jdk 'jdk17-new'
        gradle 'gradle2'
    }

    environment {
        JAVA_HOME = "tool jdk17-new"
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
