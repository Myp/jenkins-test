
properties([pipelineTriggers([[$class: 'GitHubPushTrigger']])])

node {
checkout scm
sh 'java -version'
sh './gradlew hello'
}
