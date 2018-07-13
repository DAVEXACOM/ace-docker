#!groovy

@Library('MicroserviceBuilder') _
microserviceBuilderPipeline {
  image = 'ace11da'
  mavenImage = 'wwdemo/images:maven-lab'
  chartFolder = 'https://github.com/DAVEXACOM/charts/blob/master/ibm-ace-dev'
  deployBranch = 'master/11.0.0.0/ace/ubuntu-1604/base'
  namespace = 'default'
}
