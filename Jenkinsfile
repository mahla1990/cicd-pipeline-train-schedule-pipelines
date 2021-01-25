pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "========executing build========"
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'mahi/dist/trainSchedule.zip'
            }
           
        }
    }

}
