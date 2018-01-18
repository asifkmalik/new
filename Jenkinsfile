node {
stage ('Preperation') {
    git 'https://github.com/asifkmalik/new.git'
}
stage('Build') {
    bat "gradlew.bat clean test"
}
stage('Deploy') {
    bat 'git push https://git.heroku.com/infinite-hollows-57032.git master'
}

}
