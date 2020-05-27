node {
stages {
   stage('Compile') {
   steps {
    echo "complied successfully"
}
}
stage('JUnit') {
   steps {
    echo "JUnit Passed successfully"
}
}
stage('Quality-Gate') {
   steps {
    echo "Sonarqube quality gate passed"
    /*sh exit ("1";*/
}
}
stage('Deploy') {
   steps {
    echo "pass"
}
}

}
post{
 always{
     echo 'this will always run'
}
success{
     echo 'this will run onliy if success'
}
failure{
     echo 'this will run if fail'
}
unstable{
     echo 'this will run if unstable'
}
chnaged{
     echo 'run if state CHNAGED'
}
}
}
