pipeline{

agent any

stages {
stage('code quality'){
when { tag "*" }
steps {
echo 'code quality'
}
}

stage('unit tests'){
when { tag "*" }
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
echo 'publish artifact'
}
}

}
}