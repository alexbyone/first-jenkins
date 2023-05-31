pipeline {
    agent any

    stages {
        stage('Hello') {
            input {
            
                message "Tutto Pronto?"
                ok "si"
                parameters{
                    string(name:"ENV", defaultValue: "prod")
                }
            }
            steps {
                echo "Creo l\'ambiente di ${ENV} . "
            }
        }
    }
}
