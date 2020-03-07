pipeline {
    agent {
        docker { image 'nginx:mainline-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                rm '/etc/nginx/conf.d/*'
            }
        }
    }
}
