pipeline {
  agent any
  stages {
    stage('Build') {
        steps {
            script {
                    def today = new Date()
                    def yesterday = today - 1
                    def daybeforeyesterday = yesterday.previous()
                    println "Today: " + today.format("MM/dd/yyyy") + " && Yesterday: " +
                    yesterday.format("MM/dd/yyyy") + " && The Day before yesterday: " +
                    daybeforeyesterday.format("MM/dd/yyyy")
                } 
            }
        }
    }
} 
