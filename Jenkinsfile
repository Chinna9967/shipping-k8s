#!groovy
@Library('roboshop-shared-library') _

def configMap = [
    application: "javaEKS",  // we are migrating monolithic(VM) to microservices(container,pod)
    component: "shipping"
]
// env
// // this is .groovy file name and function inside it
// // if not master branch then trigger pipeline
// if( ! env.BRANCH_NAME.equalsignorecase('master')){
// pipelineDecission.decidePipeline(configMap)
// }
// else{
//     echo "master deployment should happen through cr only"
// }
// pipelineDecission.decidePipeline(configMap)
pipelineDecission.decidePipeline(configMap)