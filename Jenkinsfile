pipeline {
agent any

stage {
stage('compile'){
steps {
sh'javac Hello.java'
}
}
stage('run') {
steps {
sh 'java hello'
}
}
}
