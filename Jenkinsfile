pipeline {
    agent any

    tools {
        maven 'mvn-3.5.4'
    }

    stages {
        stage("Build") {
            steps {
                sh "mvn clean package"
                sh "printenv"  // 将环境变量打印到控制台
            }
        }
    }
}
