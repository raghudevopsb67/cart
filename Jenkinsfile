pipeline{

agent any

stages {
stage('code quality'){
steps {
echo 'code quality'
echo 'env are down there'
sh 'env'
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
echo 'publish artifact'
}
}

}
}