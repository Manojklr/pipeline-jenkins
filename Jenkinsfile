pipeline{
agent any
stages{
stage('Build') {
steps {
sh '''
#!/bin/bash
echo "This is my first Build stage in jenkinsfile" 
'''
}
}
stage('TEST1') {
steps{
sh 'echo " This is my first test1 stage in jenkinsfile" '
}
}
stage('TEST2') {
steps{
sh ' echo "  This is my first test1 stage in jenkinsfile" '
}
}
stage('Deploy') {
steps {
sh 'echo "final deploy stage in jenkinsfile" '
}
}
}
}
