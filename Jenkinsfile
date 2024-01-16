pipeline {
    agent any

    stages {
        stage('run ansible') {
            steps {
                ansiblePlaybook installation: 'ansible', playbook: 'playbook.yml', tags: 'start', vaultTmpPath: ''            }
        }
    }
}
