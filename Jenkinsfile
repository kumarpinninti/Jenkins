node {
    stage('Git clone') {
        git 'https://github.com/kumarpinninti/ks.git'
		}
    stage('Maven validate') {
        sh 'mvn validate'
    }
	stage('Maven clean') {
        sh 'mvn clean'
    }
	stage('Maven compile') {
        sh 'mvn compile'
    }
	stage('Maven test') {
        sh 'mvn test'
    }
	stage('Maven package') {
        sh 'mvn package'
    }
}
