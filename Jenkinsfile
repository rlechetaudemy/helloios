pipeline {

    agent { label 'mac' }

    environment {
        branch = 'master'
        url = 'https://bitbucket.org/livetouchdev/helloios_udemy'
    }

    stages {
        stage('Checkout git') {
            steps {
                git branch: branch, credentialsId: 'udemy', url: url
            }
        }

        stage('Setup Fastlane') {
            steps {
                sh 'security -v unlock-keychain -p ricardo ~/Library/Keychains/login.keychain-db'

                sh 'bundle install'
            }
        }

        stage('Build') {
            steps {
                sh 'bundle exec fastlane firebase'
            }
        }
    }
}
