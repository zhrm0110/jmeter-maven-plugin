#!groovy
import groovy.json.JsonOutput
node{
    git url: 'https://github.com/zhrm0110/jmeter-maven-plugin.git'
    def mvnHome = tool 'mvn'
    sh 'mvn -B verify'
    sh 'mvn clean install'
}