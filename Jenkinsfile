pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                ant '**/build.xml'
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
