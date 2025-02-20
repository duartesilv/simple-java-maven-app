pipeline {
    agent any
    stages {
        stage('MultiBranch') {
            steps {
                echo "Current branch: ${env.BRANCH_NAME}"
            }
        }
         stage('Build Dev') {
            steps {
                echo "Deplyment in Dev..."
            }
        }
    }
}
