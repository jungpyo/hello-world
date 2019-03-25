pipeline {
    agent {
      label 'master'
    }
    stages {
        stage('Stage 1') {
            parallel {
                stage('Stage 1.1') {
                    steps {
                        echo "Running Stage 1.1"
} }
               stage('Stage 1.2') {
                    stages {
                        stage('Stage 1.2.1') {
                            steps {
                                echo "Running Stage 1.2.1"
                            }
                        }
                        stage('Stage 1.2.2') {
                            steps {
                                echo "Running Stage 1.2.2"
} }
} }
                stage('Stage 1.3') {
                    steps {
                        echo "Running Stage 1.3"
                    }
} }
} }
}              
              
