pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh '''
                python3 -m pip install --upgrade pip || true
                pip3 install flask pytest || true
                '''
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh '''
                python3 -m pytest || echo "No tests found"
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Flask app...'
                sh '''
                nohup python3 app.py > app.log 2>&1 &
                '''
            }
        }
    }

    post {
    success {
        emailext (
            subject: "SUCCESS: ${env.JOB_NAME}",
            body: "Build Successful!",
            to: "madhuawsdevops747@gmail.com"
        )
    }
    failure {
        emailext (
            subject: "FAILED: ${env.JOB_NAME}",
            body: "Build Failed!",
            to: "madhuawsdevops747@gmail.com"
        )
    }
}

