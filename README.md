# HELM_cmd
helm list
helm repo add stable https://charts.helm.sh/stable
helm repo remove stable
helm repo list
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo remove bitnami
helm search repo jenkins
helm search repo tomcat
helm search repo apache
helm search repo nginx
helm show values stable/tomcat
helm show chart stable/tomcat
helm show all stable/tomcat
sudo apt install tree
helm create podsfile
sudo apt install tree
tree podsfile
helm install testtomcat2 stable/tomcat
kubectl get pods
kubectl get all
helm install --dry-run testtomcat2 stable/tomcat
helm install --wait --timeout 20s testomcat stable/tomcat
helm install testtomcat stable/tomcat --version 0.4.0
helm list
helm install testchart2 stable/tomcat --set service.type=NodePort
helm get values testchart2
helm get manifest testchart2
helm status testchart2
helm install testchart stable/tomcat --version 0.4.0
