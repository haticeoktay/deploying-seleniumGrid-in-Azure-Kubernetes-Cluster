# Deploy Selenium-Grid version 4 in Azure Kubernetes Cluster
.yml uzantılı dosyalar önceden create edilmiştir.

kubectl config current-context

hatice-selenium

selenium-hub-svc.yml

kubectl apply -f selenium-hub-svc.yml

kubectl get services


selenium-hub-deployment.yml

kubectl apply -f selenium-hub-deployment.yml

selenium-temp.yml

kubectl apply -f selenium-temp.yml

Now you can check the grid ui at http://yourExternalIPAddress:4444/grid/console
![image](https://github.com/haticeoktay/information/assets/65062246/a9c98509-f88d-4eb6-b808-ee03c6d7af22)

selenium-node-chrome-deployment.yml

kubectl apply -f selenium-node-chrome-deployment.yml

kubectl get pods

![image](https://github.com/haticeoktay/information/assets/65062246/b0d47eff-f468-48ff-aafc-104a744c0103)






