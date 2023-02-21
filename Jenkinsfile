pipeline{

agent any

stages {

stage('code quality'){
when { branch 'main'}
steps {
echo 'code quality'
}
}

stage('unit tests'){
steps {
echo 'unit tests'
}
}

stage('prepare artifact'){
when { tag "*" }
steps {
echo 'prepare artifact'
}
}
stage('publish artifact'){
steps {
when { branch 'demo'}
echo 'publish artifact'
}
}

}
}