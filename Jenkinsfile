pipeline {
  agent any
    stages {
 
    stage('Copy Deployent & Service Defination to K8s Master') {
            KubernetesDeploy(
                Configs: "create-k8s-deployment.yaml",
                kubeconfigId: "kubernetes",
                )
            
            
        } 
         
   } 
}
