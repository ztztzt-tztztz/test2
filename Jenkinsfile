pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // 从 Git 仓库拉取代码
                sh 'ls'
            }
        }

        stage('List Files') {
            steps {
                // 列出当前目录的文件
                sh 'ls -l'
            }
        }

        stage('Echo Message') {
            steps {
                // 打印一条信息
                sh 'echo "Hello, Jenkins!"'
            }
        }
    }
}
