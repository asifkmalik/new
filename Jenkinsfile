node {
stage ('Preperation') {
git 'https://github.com/asifkmalik/new.git'
}
stage('Build') {
gradlew clean test
}
stage('Deploy') {
git push 'https://git.heroku.com/infinite-hollows-57032.git master'
}
}
