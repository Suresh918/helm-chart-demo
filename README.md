# helm-chart-demo

**Helm Commands:**
1. helm package ./ 

(It creates package helm-chart-demo-0.1.0.tgz with all the files)

2. helm install helm-chart-demo-release ./helm-chart-demo-0.1.0.tgz

(It installs the helm chart with the specified release name. It creates all the kubernetes objects in the cluster)

3. helm list

(Lists all the helm releases in the cluster)

4. helm uninstall helm-chart-demo-release

(It uninstalls the helm release. It deletes all the kubernetes objects in the cluster under this release)


role.yaml, rolebinding.yaml, management.service.yaml added as per mychange project
