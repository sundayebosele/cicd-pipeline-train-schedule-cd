Pipeline {
    agents any 
    stages {
        stage {'Build'}
        steps { 
           echo 'Build Automation Pipeline'
           sh './gradlew build --no-daemon'
           archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
