node('test-pod') {
    stage('Checkout') {
        checkout scm
    }
    stage('Build'){
        container('tomcat') {
            // This is where we build our code.
        }
    }
}
