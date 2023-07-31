pipeline{
    agent any
    stages{
        stage('Build') {
            steps {
                echo 'Building..'
        stage('Git Pull') {
            steps{
                git branch: 'main', url: 'https://github.com/sharjeelk63/titanwork.git'
            }
          } 
        }
    }
}
}
