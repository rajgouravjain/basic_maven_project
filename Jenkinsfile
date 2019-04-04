@Library('jenkins-pipeline-lib@master') _ 

import in.100m.devops.jenkins.Utilities

def utils = new Utilities(this)

node {
  utils.mvn 'clean package'
}
