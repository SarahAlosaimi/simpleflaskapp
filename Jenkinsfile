pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Install Python dependencies
                sh 'pip3 install -r requirements.txt'  // Install dependencies using pip3
            }
        }
        stage('deploy') {
            steps {
                // Run the Flask app (adjust as per your app's configuration)
                sh 'python3 app.py'  // Run the Flask app
            }
        }
    }
}
