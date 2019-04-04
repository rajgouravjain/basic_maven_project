@Library('jenkins-pipeline-lib@master') _ 

import com.example.devops.jenkins.Utilities

def utils = new Utilities(this)

node {
  utils.mvn 'clean package'
}
