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

        stage('compile code') {

            steps {

                sh 'echo "this will compile code"'
sh 'javac HelloJava.java'

            }

        }

        stage('execute code') {

            steps {

                sh 'echo "this will execute code"'
sh 'java HelloJava'

            }

        }

      

    }

}
