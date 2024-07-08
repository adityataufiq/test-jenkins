pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker run --rm -t -p 8000:8080 -e ASPNETCORE_HTTP_PORTS=8080 mcr.microsoft.com/dotnet/samples:aspnetapp'
            }
        }
    }
}
