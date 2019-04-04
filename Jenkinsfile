@Library('jenkins-pipeline-lib') 

import in.100m.devops.jenkins.Utilities

def utils = new Utilities(this)

node {
  utils.mvn 'clean package'
}
