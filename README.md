# k8s-jenkins

addresspool.yaml
 - custom addresspool range using metallb
deployment.yaml
 - deployment file for jenkins
ingress-service.yaml
 - ingress service to use port 80 and 443
namespace.yaml
 - namespace for jenkins
service-metallb.yaml
 - service metallb use to set loadbalancer and display with port 80
service.yaml
 - service to set endpoint to single resource
serviceAccount.yaml
 - Set distinct identity in the k8s cluster
volume.yaml
 - storage setup with persistenceVolume and persistenceVolumeClaim. Can be use with localhost, S3, EFS, etc.