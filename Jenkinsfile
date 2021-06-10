pipeline {

    agent {

        label 'apoorv-node'

    }

    stages {

        stage('get the code') {

            steps {

                sh 'echo "this will get me the code"'

                git 'https://github.com/apoorvdevops/hellojava'

            }

        }

        stage('second stage') {

            steps {

                sh 'echo "this will compile code"'
sh 'javac HelloJava.java'

            }

        }

        stage('third stage') {

            steps {

                sh 'echo "this will execute code"'
sh 'java HelloJava'

            }

        }

        stage('fourth stage') {

            steps {

                sh 'echo "this is fourth step"'

            }

        }

    }

}
