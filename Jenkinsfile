pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Esto es el build"
                echo "agrego otra linea"
                echo "Nuevo echo, algo mas"
            }
        }
        stage('Test') { 
            steps {
                echo "Este es el test"
                echo "A"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Este es el deploy"
            }
        }
    }
}
