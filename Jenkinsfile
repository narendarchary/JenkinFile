node {
    stage('Preparation') { // for display purposes
        // Get some code from a GitHub repository
        git credentialsId: 'git', url: 'https://github.com/narendarchary/login.git'
        // Get the Maven tool.
        // ** NOTE: This 'M3' Maven tool must be configured
        // **       in the global configuration.
    }
    stage('mvn clean') {
        // Run the maven build
        sh 'mvn clean'
    }
    stage('mvn validate') {
        // Run the maven build
        sh 'mvn validate'
    }
    stage('mvn compile') {
        // Run the maven build
        sh 'mvn compile'
    }
    stage('mvn test') {
        // Run the maven build
        sh 'mvn test'
    }
    stage('mvn pakcege') {
        // Run the maven build
        sh 'mvn pakcege'
    }
}