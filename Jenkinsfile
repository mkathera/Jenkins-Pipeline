pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                ant
            }
        }
        stage('Test'){
            steps {
      		 echo "Test phase.."     
		}
        }
        stage('Deploy') {
            steps {
                echo "Deploy phase.."
            }
        }
    }
}
