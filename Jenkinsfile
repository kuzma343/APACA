pipeline {
    agent any
    
    stages {
        stage('Install Apache') {
            steps {
                ansiblePlaybook(
                    playbook: 'install_apache.yml',
                    installation: 'Default'
                )
            }
        }
    }
}
