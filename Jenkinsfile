node() {
    stage("Budowanie") {
        checkout scm
        sh "g++ helloword.cpp"
    }
    stage("Test") {
        sh './a.out'
    }
}
