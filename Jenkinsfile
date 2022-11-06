pipeline {

    agent any

    stages{

        stage('Git clone rep'){

            steps{            
            git branch: 'main', url: 'https://github.com/zivkashtan/course.git'
            echo "stage Git clone rep done"
            }
        stage('build clean build using mvn'){

            steps{
                sh 'mvn clean install'
                echo 'build clean build using mvn'
            }
        }
        }
    }


}